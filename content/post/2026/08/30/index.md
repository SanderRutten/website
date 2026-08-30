+++
date = '2026-08-30T10:30:00+01:00'
draft = false
title = 'GL-iNet WireGuard + dnsmasq: address in use'
image = 'hero_image.jpg'
categories = ["Technology"]
tags = ["Travel"]
+++
## GL-SFT1200
I recently acquired a GL-iNet GL-SFT1200 travel router, firmware 4.8.3. A bit older model, but suitable for my occasional needs.
One disadvantage is the older software, which in this case is probably the cause of this issue.

So probably not an issue on newer models, as long as is dnsmasq at least version 2.90 if I read it correctly. The GL-SFT1200 ships with 2.80-5.

## The bug
Connecting to a WireGuard VPN would cause dnsmasq/DHCP to 'crash'. Well, technically it is running but it can't start properly. 
You can still manually configure your devices IP settings, but that is not very usable.

```
daemon.crit dnsmasq[13774]: failed to bind DHCP server socket: Address in use
daemon.crit dnsmasq[13774]: FAILED to start up
```

It appears that WireGuard creates an extra dnsmasq process, which binds to 0.0.0.0:67. Now the "lan" dnsmasq can't start because the port is already in use.

## The solution
Login via SSH:
ssh -o HostkeyAlgorithms=+ssh-rsa root@192.168.8.1
```
vi /etc/dnsmasq.conf

# Add two lines at the end
bind-dynamic
no-dhcp-interface=wgclient1

/etc/init.d/dnsmasq restart
```

Now everything should work fine again.