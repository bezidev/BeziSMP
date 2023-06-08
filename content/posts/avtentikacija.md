---
author: "BežiSMP"
title: "Avtentikacija"
date: "2023-06-08"
description: "Vse o avtentikaciji (različni tipi računov) na BežiSMP-ju."
tags: []
ShowToc: true
ShowBreadCrumbs: false
---

Strežniški administratorji si lahko izberejo, ali bi radi, da njihov strežnik preverja, če profili, ki se povezujejo na strežnik, dejansko obstajajo in so veljavni profili pri Mojangu (v nadaljevanju tudi online avtentikacija) ali pa, da strežnik ne preverja, če profili obstajajo (v nadaljevanju offline avtentikacija).

Strežnik je bil včasih postavljen v online avtentikacijo, pred kratkim pa sem naredil prehod na offline in online avtentikacijo.

## Online avtentikacija

Za vse, ki imate veljaven Minecraft/Mojang/Microsoft račun - ne potrebujete storiti ničesar, da bi se lahko povezali na strežnik. Ob prvi povezavi vas bo strežnik samodejno registriral. Če ste predhodno že igrali na tem strežniku, boste obdržali vse - nič se ne bo spremenilo.

## Offline avtentikacija

Za vse, ki nimate Minecraft računa velja naslednje:

- Lahko uporabljate zastonjske kliente (npr. TLauncher)
- Izbrati si morate tako uporabniško ime, ki še ni v registrirano pri Mojangu. To lahko preverite na [NameMC-ju](https://namemc.com/). Če ne najde uporabnika z vašim željenim uporabniškim imenom se lahko priključite.
- V primeru, da se boste poskušali priklopiti z uporabniškim imenom, ki je registrirano pri Mojangu, vas bo zavrnilo s sporočilom `Invalid session`. V tem primeru si izberite drugo uporabniško ime.
- V primeru, da se čez čas pri Mojangu ustvari uporabnik z vašim uporabniškim imenom, ta uporabnik **NE** more prevzeti vašega dosedanjega uporabniškega imena.
- V primeru, da ste kupili pravi Microsoft/Minecraft račun, lahko migrirate nanj tako, da si nastavite ime Minecraft računa na uporabniško ime, nastavljeno v BežiSMP-ju in poženete `/premium` (potem, ko ste se ročno prijavili z geslom). V primeru, da tega ne morete storiti, lahko samo prosite [strežniškega administratorja](/posts/osebje) za pomoč pri migraciji.

### Prva prijava

Ob prvi prijavi v BežiSMP, vas bo vprašalo za registracijo. Vse, kar morate narediti je to, da zaščitite svoje uporabniško ime z geslom. To geslo naj bo varno. In ne, strežniški administratorji ne morejo gledati vaših gesel, saj so haširana z SHA256 algoritmom.

Vse, kar morate narediti je, da sledite navodilom, ki se vam prikažejo na zaslonu. V primeru, da ne boste dovolj hitri, vas bo strežnik avtomatično vrgel ven iz igre.

### Nadaljnje prijave

Prijavite se z uporabo ukaza: `/login <vaše geslo>`, pri čemer `<vaše geslo>` zamenjajte z dejanskim geslom.

Vse, kar morate narediti je, da sledite navodilom, ki se vam prikažejo na zaslonu. V primeru, da ne boste dovolj hitri, vas bo strežnik avtomatično vrgel ven iz igre.

## Bedrock avtentikacija

Vsi računi, ki se pridružujejo iz Bedrock klienta dobijo pred ime piko (`.`), da se lahko razlikujejo od Java računov. Bedrock podpora je eksperimentalna, zato kontaktirajte [strežniškega administratorja](/posts/osebje) v primeru težav.

Vsi Bedrock računi se avtenticirajo po principu [Offline avtentikacije](#offline-avtentikacija).

## Za vse

V primeru, da bi radi migrirali svoje stvari iz enega računa na drugega, kontaktirajte [strežniškega administratorja](/posts/osebje).

## Težave pri prijavi

- Če ste online igralec, pa od vas zahteva geslo, je to zmota strežnika. Disconnectajte se iz igre in čez nekaj sekund ponovno prijavite. Na ta način bi moralo delovati, drugače pa kontaktirajte [strežniškega administratorja](/posts/osebje).
- V primeru težav pri prijavi, lahko kontaktirate [strežniškega administratorja](/posts/osebje) preko elektronske pošte ali Discorda.

## Zgodovina avtentikacije

Na žalost sem kot strežniški administrator na začetku pozabil ugasniti online avtentikacijo, ko smo začeli s strežnikom pa so igralci kar naprej prihajali, dokler nisem naletel na igralce, ki niso imeli Minecraft računov. Ker so tudi oni radi igrali, sem predlagal naj strežnik preklopimo na offline avtentikacijo, za kar bi porabil kako uro, s tem, da bi se mi morali vsi igralci počasi priklapljati in odklapljati iz strežnika, da bi jim premaknil inventorije iz starih Mojangovih UUID-jev na offline UUID-je.

To je vsekakor kompleksno pravilo, ki sem ga bil pripravljen opraviti, a so ga kljub temu, da ne bi bilo skoraj nič drugače (razen tega, da ne bi imeli dostopa do tega računa kjerkoli drugje kot na svojem računalniku), v Discord serverju večinsko zavrnili. Res mi je bilo žal, ampak nisem kar tako moral premakniti inventorijev brez sodelovanja ljudi. Ne vem, kaki so njihovi argumenti za odločitev, ampak sem upošteval glas ljudstva.

Na koncu so tisti igralci brez Minecraft računa morali igrati preko "zastonjskih" računov na [EasyMC](https://easymc.io/). Ti so večinoma bannani iz večjih strežnikov, ampak ne iz BežiSMP-ja, tako da so se lahko vseeno povezali gor.
