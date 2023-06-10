---
author: "BežiSMP"
title: "Strežnik"
date: "2023-06-11"
description: "Generalno o strežniku in strežniški namestitvi."
tags: []
ShowToc: false
ShowBreadCrumbs: false
---

## Strežniške specifikacije

Strežniške specifikacije so naslednje:

- Procesor: AMD Ryzen 7 5700G
- Grafična kartica: integrirana AMD Radeon Vega grafika (zakaj bi v serverju potreboval zunanjo grafiko???)
- RAM: 2x16GB (od tega konstantno alociranega 6GB in največ 10GB alociranega za Minecraft strežnik, _lahko tudi povečam na pobudo skupnosti_) DDR4-3200
- Trdi disk: en generic M.2 PCIe 1TB SSD (Crucial?)
- Matična plošča: ena random Gigabyte B550M plošča
- Operacijski sistem: Fedora Server 37 (a kaj obžalujem, da nisem šel Ubuntu/Debian? Malo, ampak veliko tudi ne.)
- ISP: Telemach... (upam, da bo kdaj IPv6)
- Minecraft strežnik: Paper 1.20 (fork Spigota)

Torej server **NE BO** laggal dokler ne boste gradili lag mašin.

## Ugašanje strežnika

Strežnik se ugasne vsak dan ob 4.00. Strežnik se vrne nazaj čez nekaj minut. Ob tej uri se ponovno zažene, ker takrat _naj ne bi_ nihče igral, poleg vsega pa je treba sprostiti malo RAM-a.

## Plugini

- [InvSee++](https://www.spigotmc.org/resources/invsee.82342/) (za dajanje stvari nazaj ob strežniškem lagu)
- [Graves](https://www.spigotmc.org/resources/graves.74208/) (na pobudo skupnosti, saj so raje imeli malo manj raztreščene stvari, ko so se med sabo pobijali)
- [AuthMe Reloaded](https://github.com/AuthMe/AuthMeReloaded) za avtentikacijo offline igralcev
- [FastLogin](https://github.com/games647/FastLogin) za avtentikacijo online igralcev
- [Simple Voice Chat](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat) za voice chat
- [Geyser in Floodgate](https://geysermc.org/download) za Bedrock igralce
- [ViaVersion](https://github.com/ViaVersion/ViaVersion) za eksperimentalno podporo za novejše Minecraft kliente

## Generalno

- keepInventory **NI** prižgan. Ko umrete, se vam na točki smrti pojavi grob, ki se izbriše po okoli treh urah.
- Za prespanje noči je potreben samo en igralec.
