---
layout: page
title: Webex dolgozat/szavazás kérdőív szerkesztő (Webex Poll Questionnaire Editor) használata
permalink: /dolgozat_szavazas_kerdoiv_szerkeszto
---

# Webex dolgozat/szavazás kérdőív szerkesztő funkciója

A Webex Meetingek (akár Meeting, akár Training, akár Event) egyik visszajelzési lehetősége a szavazások (Poll) indítása. A szavazások elkészítésére lehetőség van a meeting közben, de a Webex dolgozat/szavazás kérdőív szerkesztő (Webex Poll Questionnaire Editor) használtával előre elkészített fájlokból is van lehetőség importálni a kérdéseket és a válaszokat.

Ennek iskolai felhasználása több területen is történhet:

* Lehetőség van akár számonkérés indítására is mivel a teszt kitöltését időkorláthoz lehet kötni. 
* Jelenléti ív vezetésére is lehet használni.
* Visszajelzést lehet kapni az óráról, stb.

Ezen dokumentáció bemutatja a Webex dolgozat/szavazás kérdőív szerkesztő letöltését, telepítését, használatát és eltávolítását.

A Webex Poll Questionnaire Editor Windows operációs rendszerekhez érhető el.

# Webex dolgozat/szavazás kérdőív szerkesztő letöltése

El kell látogatni a [Webex honlap](https://www.webex.com)-ra. A felhasználói adatokkal történő bejelentkezés után a bal oldali menüsorban ki kell választani a Webex Events menüpontot:

![Select Webex Events](/assets/img/pollquestionnaire/selectwebexevents.png)

A megjelenő Webex Events oldalon a bal oldali menüsorban ki kell választani a Support / Downloads menüpontot, majd a középső részben lenyitni a Webex Poll Questionnaire Editor részt és a Download gombra kattintani.

![Download](/assets/img/pollquestionnaire/download.png)

[Közvetlen link](https://akamaicdn.webex.com/client/WBXclient-40.2.10-14/polleditor.msi) ami jelen dokumentáció elkészítésekor működik (verzióváltás miatt elképzelhető hogy későbbiekben nem lesz elérhető).

# Webex dolgozat/szavazás kérdőív szerkesztő telepítése

A telepítést a __polleditor.msi__ filera történő dupla kattintással lehet megkezdeni.

![Install step](/assets/img/pollquestionnaire/install1.png)

A megjelenő ablakban a “Next” gombra kell kattintani

![Install step](/assets/img/pollquestionnaire/install2.png)

A következő ablakban (a licenc megállapodás elolvasása után) ki kell választani az __“I accept the terms in the licence agreement”__ rádiógombot majd a __“Next”__ gombra kattintani

![Install step](/assets/img/pollquestionnaire/install3.png)

A __“Complete”__ telepítési módot kell bejelölve hagyni és a __“Next”__ gombra kattintani.

![Install step](/assets/img/pollquestionnaire/install4.png)

A __“Change”__ gombbal módosítható a telepítés útvonala, amennyiben megfelelő akkor a __“Next”__ gombra kell kattintani.

![Install step](/assets/img/pollquestionnaire/install5.png)

Az __“Install”__ gombbal indítható a telepítés. Az esetlegesen megjelenő biztonsági kérdésre az __“Igen”__ vagy __“Yes”__ gombot kell megnyomni a telepítés megerősitéséhez.

![Install step](/assets/img/pollquestionnaire/install6.png)

A telepitést a __“Finish”__ gombbal lehet befejezni.

# Webex dolgozat/szavazás kérdőív szerkesztő használata

A Webex Poll Questionnaire Editor-t a Start Menüben lehet elindítani.

Az indítás után az alábbi képernyő jelenik meg:

![Usage](/assets/img/pollquestionnaire/usage1.png)

A Megnyitás gombra ![Open](/assets/img/pollquestionnaire/folder_small.png) (vagy a File/Open menüpontra) kattintva már korábban elmentett kérdőív betöltésére van lehetőség.

![Usage](/assets/img/pollquestionnaire/usage2.png)

Új kérdés létrehozására az alábbi részben van lehetőség:

![Usage](/assets/img/pollquestionnaire/usage3.png)

A kérdés lehet több választásos (Multiple choice) vagy Rövid válaszos (Short answer)

A több választás esetében lehet 1 (Single Answer) vagy több helyes választ (Multiple Answers) is megadni. Ezt a legördülő menüben lehet kiválasztani.

Fentiek eldöntése után az új kérdést a New gombra kattintással lehet elkészíteni.

![Usage](/assets/img/pollquestionnaire/usage4.png)

Ugyanitt a válaszokat is meg lehet adni:

![Usage](/assets/img/pollquestionnaire/usage5.png)

A helyes válasz kijelölésére a válasz kiválasztásával és __“Mark as Correct”__ gombra kattintással van lehetőség

![Usage](/assets/img/pollquestionnaire/usage6.png)

A helyes válasz kiválasztása után egy zöld pipa kerül a betűjele elé. Természetesen nem kötelező helyes választ jelölni, pl egy sima kérdőívnél.

Új kérdés hozzáadására a New gombra kattintással van lehetőség:

![Usage](/assets/img/pollquestionnaire/usage7.png)

Több helyes válasz esetén a _Mark as Correct_ gombbal több lehetőséget is be lehet jelölni.

A _“Record individual responses”_ bejelölésével minden egyes válasz külön külön el lesz mentve. Erre nincs szükség egy kérdőívnél ahol csak a végeredményre van szükségünk.

Az ablak alján található __“Options…”__ gomb megnyomása után az alábbi beállításokat változtathatjuk meg:

![Usage](/assets/img/pollquestionnaire/usage8.png)

Itt állíthatjuk be az időzítőt. Az időzítés lejárta után nincs lehetőség további válaszokat beküldeni. Alapértelmezetten ez 5 percre van állítva.

Az _Edit_ gombbal ![Usage](/assets/img/pollquestionnaire/edit_small.png) lehetőség van a kérdések és válaszok szerkesztésére. Az éppen kiválaszott kérdést vagy választ fogja szerkeszteni.

A Delete gombbal ![Usage](/assets/img/pollquestionnaire/delete_small.png) lehetőség van az aktuális kérdés vagy válasz törlésére.

A _Fel_ és _le_ ![Usage](/assets/img/pollquestionnaire/up_down_small.png) gombokkal a kérdések és válaszok sorrendjét lehet változtatni, az éppen kijelölt kérdést vagy választ mozgatva fel illetve le.

A _Mentés_ gombbal ![Usage](/assets/img/pollquestionnaire/save_small.png) lehet elmenteni a kérdőívet. Ha ez első mentés akkor meg kell adni a file nevet és útvonalat.

A _Clear All_ gomb töröl mindent a listából (kérdések és válaszok). Nem kérdez vissza, ezért óvatosan használandó.

## Menüpontok:

File – Open – megnyitja a korábban elmentett .ATP filet.

File – Save – Elmenti az aktuális kérdőívet (ha első mentés akkor meg kell adni a file nevet és útvonalat)

File – Save As - Elmenti az aktuális kérdőívet más néven

File – Exit – kilép az alkalmazásból

Help – About Poll Editor – Az alkalmazás adatainak megtekintése.

# Webex dolgozat/szavazás kérdőív szerkesztő eltávolítása

Az alkalmazás eltávolítását a _polleditor.msi_ filera történő dupla kattintással lehet megkezdeni.

![Usage](/assets/img/pollquestionnaire/uninstall1.png)

A __“Next”__ gombot kell megnyomni

![Usage](/assets/img/pollquestionnaire/uninstall2.png)

Az eltávolítás a __“Remove”__ rádiógomb kiválasztásával és a __“Next”__ gombra történő kattintással kezdhető meg.

![Usage](/assets/img/pollquestionnaire/uninstall3.png)

A __“Remove”__ gombra kattintva elkezdődik az eltávolítás. A __“Cancel”__ gombbal megszakítható a folyamat. A __“Back”__ gombbal az előző képernyő található beállításokat lehet módosítani.

![Usage](/assets/img/pollquestionnaire/uninstall3.png)

A __“Remove”__ gombra kattintás után esetlegesen megjelenő  biztonsági kérdésre __“Igen”__ vagy __“Yes”__ gomb megnyomásával kezdődik meg az alkalmazás teljes eltávolítása.