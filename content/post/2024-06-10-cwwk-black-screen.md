---
title: 'CWWK Black Screen'
date: '2024-06-10T16:43:00+01:00'
tags: ["Black Screen", "TopTon", "CWWK"]
bigimg: [{src: "/images/2024/06/10/post_image.jpg"}]

---

## CWWK/TopTon black screen 
Recently I have bought a [CWWK X86 P5 SUPER Mini PC](https://cwwk.net/collections/frontpage/products/cwwk-x86-p5-super-mini-router-12th-gen-intel-n100-ddr5-4800mhz-firewall-pc-2x-i226-v-2-5g-lan-fanless-mini-pc) for my [OPNSense](https://opnsense.org) firewall.
I bought the machine without storage and RAM, so I needed to provide my own.

My first idea was to replace my current [Proxmox](https://proxmox.org) homeserver so I went with 32GB of RAM.
Later I decided that I only wanted my firewall on this machine, so I didn't need much RAM and bought 8GB.
The memory modules I did test are
[Corsair VENGEANCE DDR5 SODIMM 32GB](https://www.corsair.com/us/en/p/memory/cmsx32gx5m2a4800c40/vengeance-ddr5-sodimm-32gb-2x16gb-ddr5-4800-pc5-38400-c40-1-1v-cmsx32gx5m2a4800c40)
and [Crucial RAM 8GB DDR5](https://eu.crucial.com/memory/ddr5/ct8g48c40u5).

Both worked fine, but..
A small PSA: When you first powered on the machine, or when changing memory, the first boot takes about a minute, without any beeps. Just a black screen. 
Every next boot is normal.

It is possible that this is also the case with other models and/or TopTon or other rebrands of this machine.
