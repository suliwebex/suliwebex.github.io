---
layout: page
title: Telepítés MacOS-re
permalink: /install/macos
---

[![alt text](/assets/img/button_macos-utmutato-letoltese.png)](/assets/install/macos.pdf)

# A Cisco Webex alkalmazás telepítése

A Cisco Webex alkalmazást kétféleképpen is lehet használni:

* Online - Böngészőn keresztül
* Offline – Letöltött alkalmazásból

## Online

Online a következő linken tudjuk elérni a Cisco Webex-et: [Webex](https://globalpage-prod.webex.com/signin?surl=https%3A%2F%2Fsignin.webex.com%2Fcollabs%2Fauth%3F){:target="_blank"}

Ha van már meglévő Webex-es profilunk akkor jelentkezzünk be, ha nincs akkor
csináljunk.

## Offline

Offline pedig úgy, hogy letöltjük az alkalmazás applikációját a következő oldalról: [Letöltés](https://www.webex.com/downloads.html/){:target="_blank"}
Vagy akár az App Store-ban is megtalálhatjuk és leszedi az alapértelmezett applikációt amit telepít is.

### Offline telepítési példa

Miután megnyitjuk a fent említett oldalt a letöltés vagy Download for macOS gombra kattintva felugrik egy ablak ahol elég csak OK-ot nyomni.

![step 1](/assets/img/install/macosinstall1.png)

Ezután a következő lépés fogad minket miután letöltötte a böngésző a program telepítőcsomagját. Itt csak dupla kattintással elindítjuk a telepítést.

![step 2](/assets/img/install/macosinstall2.png)

Maga a telepítés lényegében három kattintással meg lehet csinálni. __„tovább, Tovább, Ok”__. Telepítés után meg fog nyílni a Webex:

![step 3](/assets/img/install/macosinstall3.png)

__Ahhoz, hogy minél zökkenőmentesebben tudjuk használni a Cisco Webex videókonferenciai eszközt egy-két kritériumnak meg kell felelnünk.__

## A Hálózati kapcsolat ellenőrzése

* Kábeles:
Ez problémás lehet Macbook Air-ek és frissebb Pro-k esetében hisz ezeknek nincs közvetlen hálózati portjuk. Kell hozzájuk átalakító.
Azoknál a Macbook-oknál amiken nincs hálózati port egyszerűbb csak a Wi-Fi beállítást használni.
Ha van (vagy van átalakítónk) akkor csatlakoztassuk a gépet a hálózati kábel segítségével és automatikusan csatlakozni fog.
* Wi-Fi:
Vezeték nélküli csatlakozás esetén az általunk ismert és használt Wi-Fi kapcsolatra kell csatlakoznunk a tálcán, a hálózati jelnél és megadni a hozzátartozó jelszót.

![step 4](/assets/img/install/macosinstall4.png)

## A hálózati sebesség ellenőrzése

* Az alap minőséghez a minimum sávszélesség:
  * Letöltés: 0.5 Mbps 
  * Feltöltés: 0.5 Mbps
* A magas minőséghez a minimum sávszélesség:
  * Letöltés: 1.0 Mbps 
  * Feltöltés: 1.5 Mbps
* A HD minőséghez a minimum sávszélesség:
  * Letöltés: 2.5 Mbps 
  * Feltöltés: 3.0 Mbps
* A következő oldalon ajánlott a tesztelése: [speedtest](https://www.speedtest.net){:target="_blank"}
*A sebesség lehet eltérő internetszolgáltatók és azoknak a csomagjai különbsége miatt is.

## Cisco Webex hálózati tesztelése

* Ehhez a [mediatest](https://mediatest.webex.com){:target="_blank"} oldalt kell megnyitnunk.
* Ahhoz, hogy sikeresen tesztelni tudja az oldal érdemes Google Chrome 39-es vagy frissebb vagy Mozilla Firefox 28-as vagy frissebb verziójú böngészőt használni.

![step 5](/assets/img/install/macosinstall5.png)

## Webex infrastruktúra elérhetőségi riportja

* Az elérési útvonala a következő: [Webex status](http://status.webex.com){:target="_blank"}
* Itt tudjuk ellenőrizni a hibaelhárítás alatt lévő hibákat és a szerveroldali működését a Cisco Webex-nek.

## A hangszóró, fejhallgató és mikrofon beállítása

* Ezt a Hang (Sound) opció alatt tudjuk megtenni.
* Legegyszerűbben a Command + Space gombok használatával előhozzuk a Spotlight keresőt és beírjuk, hogy Hang vagy Sound rendszernyelvtől
függően.

![step 6](/assets/img/install/macosinstall6.png)

* A Hangon (Sound) belül nekünk a Kiviteli és a Beviteli (Input) fülek lesznek a lényegesek hisz a Kiviteli (Output) eszköz ügye lehet a gép hangszórója, hangfal vagy akár a headsetünk is míg a beviteli eszköz jelen esetben a mikrofonunk lesz.

![step 7](/assets/img/install/macosinstall7.png)

* Ha csatlakoztatunk akár Jack dugóval vagy Bluetooth-al kiviteli vagy beviteli eszközt azok az ottlévő felsorolásban szerepelni fognak és kitudjuk őket választani. Kiválasztás után az lesz az alapértelmezett eszköz egészen a leválasztásig.
* Bluetooth-os eszköz csatlakoztatásához be kell, hogy kapcsolva legyen a Bluetooth a gépünkön amit a Command + Space – Spotlight keresőben a Bluetooth résznél tudunk ellenőrizni. Eszközt is itt tudunk felvenni a Bluetooth-os eszközünk párósítását elindítva megfog jelenni a listában és csak rá kell menni a párosításra. Utána már a tálcán lévő Bluetooth gomb segítségével egyszerűbben is tudjuk párosítani a két eszközt. (ha az eszköz bekapcsolásakor automatikusan nem csatlakozik fel a Macbookra)

![step 8](/assets/img/install/macosinstall8.png)

* A mikrofon működését a Beviteli (Input) fül alatt a Beviteli szint (Input level) mutatja, hogy ha érzékeli a beszédünket.

![step 9](/assets/img/install/macosinstall9.png)

* A mikrofon engedélyezését még a Security & Privacy alatt is tudjuk ellenőrizni esetleg ha kell tiltani.

![step 10](/assets/img/install/macosinstall10.png)

* Itt kitudjuk választani a Beviteli eszközt is, ha külön csatlakoztattunk esetleg mikrofont a Macbook-hoz. (Jack Headset esetén automatikusan átáll arra)

## Képernyő beállítások ellenőrzése

* Ezt a Kijelzők (Displays) opció alatt tudjuk megtenni 
* Command + Space – Spotlight keresőbe beírva tudunk a leggyorsabbaneljutni ehhez az opcióhoz.

![step 11](/assets/img/install/macosinstall11.png)

* Ha több kijelzőnk van a gépre csatlakoztatva akkor kitudjuk választani őket itt és egyesével beállítani, hogy melyiknek milyen felbontása legyen plusz, hogy tükrözve akarjuk a képet használni vagy külön kijelzőként.

## Kamera beállításainak ellenőrzése

* A Security & Privacy opció alatt találjátok meg a Kamerát és hogy minek van engedélye használni azt. Itt érdemes hozzáadni a Cisco Webex-et.
Majd utána működni fog a kamera az alkalmazáson belül.

![step 12](/assets/img/install/macosinstall12.png)

Továbbá a hardveres és a szoftveres kritériumok megtekinthetőek a következő hivatalos
oldalon: [Rendszerkövetelmények](https://help.webex.com/en-us/nki3xrq/Webex-Meetings-Suite-System-Requirements){:target="_blank"}
