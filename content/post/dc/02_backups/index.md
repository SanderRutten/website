+++
date = '2026-09-01T12:00:00+02:00'
draft = false
title = 'Backups'
image = 'hero_image.jpg'
categories = ["Digitaal Café"]
tags = ["Help"]
toc = "true"
url = "/help/:slug/"
+++
## Introductie
Een veelgehoorde strategie voor backups is de 3-2-1 backup strategie.
<!-- Reversed lijst: 2 spaties op het eind! -->
3\. Bewaar 3 kopieën van uw bestanden (1 origineel, 2 kopieën)  
2\. Bewaar 2 verschillende opslag apparaten (Laptop, smartphone, externe schijf, USB stick, CD/DVD)  
1\. Bewaar 1 kopie buitenshuis (Familie, schuur, cloud)  

De 2 opslag apparaten mogen best 2 externe hardeschijven zijn. De boodschap is hier: Zet niet 2 kopiën op hetzelfde apparaat. 

> [!CAUTION] Voorzichtig 
> Let op, voornamelijk bij CD/DVD kan na verloop van tijd de data mogelijk onleesbaar worden door [bitrot](https://nl.wikipedia.org/wiki/Bitrot). Donker bewaren voor een langere levensduur is hier het advies.

Voor de meeste mensen is een externe hardeschijf van 500GB waarschijnlijk al ruim voldoende. Deze zijn momenteel te koop rond de 50 euro. Koop bij voorkeur 2 schijven: 1 schijf voor thuis, en 1 voor een locatie buitenshuis.

Als u ervoor kiest om toch maar 1 backup/kopie te maken, zorg er minimaal voor dat die buitenshuis wordt bewaard. In geval van diefstal/verlies of brand bent u anders uw backup kwijt, en mogelijk ook het origineel. Daarom nogmaals het advies voor de extra schijf die buitenshuis bewaard wordt. Een defecte schijf is minder erg, het origineel is er immers nog, naast één van de twee backup schijven.

<!-- ## Externe USB hardeschijf/stick
Een externe USB hardeschijf of USB stick zijn de makkelijkste methodes voor een backup.
Windows kan automatisch bakcups maken als een ingesteld opslagapparaat is gevonden.

Nog even uitzoeken.
Bestandsgeschiedenis > Kies schijf > Inschakelen.
-->

## Netwerk hardeschijf (NAS)
Een geadvanceerde versie van een externe schijf is de NAS, een apparaat met één of meer hardeschijven, verbonden met uw netwerk. U kunt dan via Windows Verkenner / Apple Finder bladeren alsof het een hardeschijf in uw computer is. Nadeel is de hoge initiële aanschaf en vereist meer kennis.

De diverse fabrikanten (Bijv [Synology](https://synology.com), [QNAP](https://qnap.com), [UGREEN](https://ugreen.com)) bieden ook mobiele apps aan om uw bestanden te synchroniseren met de NAS. Daarnaast bieden ze meestal ook een specifieke foto-applicatie aan om alleen foto's en video's te synchroniseren.
Standaard werken deze apparaten alleen vanaf uw eigen netwerk, met enige netwerkkennis is dit ook mogelijk vanaf het internet. 

Ik ga ze verder niet in detail beschijven, ter info dat ze bestaan.

## Cloud opslag
Er zijn diverse cloud-opslag aanbieders die ook software aanbieden om automatisch uw bestanden naar de cloud te synchroniseren. Daarnaast hebben ze ook mobiele applicaties beschikbaar zodat u ook gegevens op uw telefoon kunt synchroniseren met de cloud. Voorbeelden daarvan zijn 
[Google Drive](https://workspace.google.com/intl/nl-NL/products/drive/), 
[Microsoft OneDrive](https://www.microsoft.com/nl-nl/microsoft-365/onedrive/online-cloud-storage), [Proton Drive](https://proton.me/drive) of [Dropbox](https://dropbox.com).

> [!WARNING] Waarschuwing
> Een cloud-opslag applicatie zal over het algemeen constant controleren of er bestanden zijn gewijzigd en direct gaan synchroniseren. Als u bestanden (per ongeluk) verwijderd of een virus oploopt die bestanden versleuteld zal dit vrijwel onmiddelijk ook in de cloud gebeuren.
>
> In die zin is het daarom geen goede backup optie.

## Google Fotos
Deze optie backupt alleen uw foto's en video's, niet uw overige data.

Installeer Google Foto’s via de [Play Store (Android)](https://play.google.com/store/apps/details?id=com.google.android.apps.photos) of de [App Store (iOS)](https://apps.apple.com/nl/app/google-fotos/id962194608) en log in met je Google-account. Foto’s en video’s worden daarna automatisch geback-upt.

Gebeurt dit niet automatisch: 
- Tik rechtsboven op uw profiel-foto 
- Kies voor ***Instellingen voor Foto’s > Back-up***.
- Tik op ***Back-up staat uit*** om aan te zetten.

Standaard worden alleen bestanden uit de ***DCIM***-map opgeslagen; via ***Standaard back-up > Apparaatmappen*** kun je extra mappen toevoegen.

> [!WARNING] Waarschuwing
> Google Fotos heeft een optie om ruimte op uw telefoon vrij te maken. Dit zijn bestanden die reeds zijn geupload naar Google Fotos. Dit zijn echter de orignele bestanden die opgeschoond worden!

## Apple iCloud
De iCloud van Apple kan zowel uw bestanden als foto's en video's syncrhoniseren.
Dit werkt officieel alleen op Apple apparaten. Apple heeft geen Android app, al zijn er wel onofficiële apps in de Google Play Store te vinden. Wel is er een [iCloud for Windows](https://support.apple.com/en-us/103232) beschikbaar.
Of je kan inloggen op de [website](https://icloud.com) om bestanden of foto's te bekijken, downloaden en uploaden.

Als u een iPhone, iPad of Mac heeft bent u waarschijnlijk al ingelogd met uw Apple Account en is de kans groot dat iCloud al aanstaat. Kijk op de Apple Support: [iCloud instellen op al je apparaten](https://support.apple.com/nl-nl/guide/icloud/mmfc0f1e2a/1.0/icloud/1.0) pagina om te controleren of dit is ingesteld.