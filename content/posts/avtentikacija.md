---
author: "BežiSMP"
title: "Avtentikacija"
date: "2023-05-01"
description: "Izbira ni bila ravno prava (ali pač)."
tags: []
ShowToc: false
ShowBreadCrumbs: false
---

Strežniški administratorji si lahko izberejo, ali bi radi, da njihov strežnik preverja, če profili, ki se povezujejo na strežnik, dejansko obstajajo in so veljavni profili pri Mojangu (v nadaljevanju tudi online avtentikacija) ali pa, da strežnik ne preverja, če profili obstajajo (v nadaljevanju offline avtentikacija).

Na žalost sem kot strežniški administrator pozabil ugasniti online avtentikacijo, ko smo začeli s strežnikom pa so igralci kar naprej prihajali, dokler nisem naletel na igralce, ki niso imeli Minecraft računov. Ker so tudi oni radi igrali, sem predlagal naj strežnik preklopimo na offline avtentikacijo, za kar bi porabil kako uro, s tem, da bi se mi morali vsi igralci počasi priklapljati in odklapljati iz strežnika, da bi jim premaknil inventorije iz starih Mojangovih UUID-jev na offline UUID-je.

To je vsekakor kompleksno pravilo, ki sem ga bil pripravljen opraviti, a so ga kljub temu, da ne bi bilo skoraj nič drugače (razen tega, da ne bi imeli dostopa do tega računa kjerkoli drugje kot na svojem računalniku), v Discord serverju večinsko zavrnili. Res mi je bilo žal, ampak nisem kar tako moral premakniti inventorijev brez sodelovanja ljudi. Ne vem, kaki so njihovi argumenti za odločitev, ampak sem upošteval glas ljudstva.

Na koncu so tisti igralci brez Minecraft računa morali igrati preko "zastonjskih" računov na [EasyMC](https://easymc.io/). Ti so večinoma bannani iz večjih strežnikov, ampak ne iz BežiSMP-ja, tako da so se lahko vseeno povezali gor.

V _bližnji_ prihodnosti načrtujem nek proxy za offline avtentikacijo. Vsi s pravimi Mojang accounti bi se lahko povezali preko online avtentikacije, vsi ostali pa avtomatično preko offline avtentikacije, za zdaj pa mi je žal če nimate Minecraft računa, ampak boste očitno morali uporabljati online avtentikacijo preko katere izmed storitev.
