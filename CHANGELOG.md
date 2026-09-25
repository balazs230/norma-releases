# Norma changelog

## 2026-09-25-1427 — 2026-09-25

- Új beszállító: **Hidropneumat** (horvát teherautó-, hidraulikai és pneumatikai alkatrészek, euróban), a Beszállítók fülön. A kártyáján jelentkezz be, vagy add meg a belépési adataidat. A fiókod árát hasonlítjuk össze: a webshop a rendeléseidre nem számol áfát, ezért nettó árként kezeljük. A webshop nem jelöl OEM megfelelőket, és a keresése a termékek nevében és leírásában is keres, ezért a más cikkszámú találatok (például a kódot tartalmazó szűrőkészletek) bizonytalanként, átnézésre jelennek meg.
- Inter Cars: a sok webshopot egyszerre kereső összehasonlításban a keresés ritkábban szakad meg „Az oldal megváltozott” vagy „Keresés sikertelen” hibával; a lassabban betöltődő árakra tovább várunk.
- Inter Cars: a gyári alkatrészek („OE HONDA”, „OE OPEL” …) gyártója az autógyártó neve, így ha a keresésben gyártót is megadsz (pl. Honda), a gyári cikk pontos találatnak számít.
- Unix Auto: a gyári alkatrészeknél a webshop nem adja meg a cikkszámot, ezért ezek nem számíthatnak pontos találatnak; az ajánlatnál ezt külön jelezzük.
- A webshopok „Keresésben” jelölése megmarad: amit kiveszel a keresésből, az az oldal frissítése és az újraindítás után is kimarad, amíg vissza nem jelölöd.
- Új beszállító: **Winkler** (német teherautó-, busz- és mezőgazdasági alkatrészek, euróban), a Beszállítók fülön. A kártyáján jelentkezz be, vagy add meg a belépési adataidat. Az áfa nélküli vevői árat hasonlítjuk össze; más gyártó cikke akkor számít OEM megfelelőnek, ha a webshop szerint a keresett kódon keresztül találta meg.
- Új beszállító: **DieselDR** (magyar teherautó- és buszalkatrészek, forintban), a Beszállítók fülön. A kártyáján jelentkezz be, vagy add meg a belépési adataidat. A nettó eladási egységárat hasonlítjuk össze; OEM megfelelőnek azok a cikkek számítanak, amelyeket a webshop a keresett cikk termékoldalán alternatívaként listáz. A webshop nem ad meg gyártót, ezért a gyártó üres marad.
- Új beszállító: **Martex** (lengyel teherautó-alkatrészek, euróban), a Beszállítók fülön. A kártyáján jelentkezz be, vagy add meg a belépési adataidat. A nettó vevői árat hasonlítjuk össze, ha a webshopban a „Prices client” (vevői árak) megjelenítés van beállítva. Egy kód keresése itt fél percig is eltarthat, mert az OEM megfelelőket egyenként ellenőrizzük a webshop termékadatlapjain.
- Új beszállító: **AutoS** (lengyel teherautó-alkatrészek, euróban), a Beszállítók fülön. A kártyáján jelentkezz be, vagy add meg a belépési adataidat. A kereséskor egy böngészőablak nyílik meg, mert a webshop a háttérben futó böngészőt nem engedi be. A nettó vevői árat hasonlítjuk össze; más gyártó cikke akkor számít OEM megfelelőnek, ha a webshop a keresett kód katalógusszáma alatt vagy helyettesítőjeként listázza.
- Új beszállító: **Suder** (lengyel teherautó- és pótkocsi-alkatrészek, euróban), a Beszállítók fülön. A kártyáján jelentkezz be, vagy add meg a belépési adataidat. A nettó árat hasonlítjuk össze; ha a webshop a nettó és a bruttó árat azonosnak mutatja, azt az ajánlatnál jelezzük. Más gyártó cikke csak akkor számít OEM megfelelőnek, ha a webshop termékoldala a keresett kódot a cikk számai között listázza.
- A **Vos Truckparts** a Beszállítók fülre került: az árai az összesítésben a beszállítói oldalon szerepelnek.
- Új **Összesítés** a fülek alatt: alkatrészenként a legolcsóbb versenytársi és beszállítói ár egymás mellett, a különbséggel RON-ban és százalékban (zöld: a beszállító olcsóbb, piros: egy versenytárs olcsóbb). Saját Excel-exportja van.
- Közös keresés: a keresőmező a lap tetejére került, és egy összehasonlítás egyszerre keres a versenytársaknál és a beszállítóknál. Alatta a **Versenytársak** és a **Beszállítók** fül a webshopok kártyáit és az eredményeket csoportonként, külön mutatja; az Excel- és CSV-export az éppen nyitott fül eredményét tartalmazza. A korábbi összehasonlítások a keresőmező alatti listából választhatók.

## 2026-09-24-1336 — 2026-09-24

- Inter Cars és HIFI FILTER: javítottuk az ismétlődő emberi ellenőrzést okozó böngészőindítást. Bejelentkezéskor a webshop önálló böngészőablakban fut. Az ellenőrzés és a belépés után hagyd nyitva az ablakot, majd a Normában válaszd a **Mentés és böngésző bezárása** gombot. Csak a sikeres bejelentkezést mentjük; egy félbehagyott ellenőrzést nem jelölünk késznek.
- Új versenytárs: **AICAT (Augsburg)**. A saját nettó és bruttó árakat, a raktárkészletet és a webshop által jelölt alternatívákat is lekérjük. A bejelentkezés és a keresés külön, látható böngészőablakban fut; a belépési adatok a kártyán elmenthetők.
- Az Excel-exportban új munkalap: **Legolcsóbb ajánlatok**. Alkatrészenként egy sort tartalmaz, a legolcsóbb ajánlattal (ugyanazzal, amelyet a táblázat „Legolcsóbb ajánlat” oszlopa mutat). Az összes ajánlat továbbra is az első munkalapon található.
- EUTruckParts: megbízhatóbb keresés, amikor a webshop lassan válaszol. A Norma tovább vár az első találati oldalra, a további oldalakat egyszerre tölti be, és ha ezek közül egy nem érkezik meg időben, a már beolvasott találatokat megtartja, jelezve, hogy a lista hiányos lehet.
- A legolcsóbb ajánlat kiemelése (a soronkénti halványzöld is) csak olyan ajánlatra kerül, amelynél a webshop készletet vagy szállítási határidőt ad meg. Ha egy nem elérhető vagy ismeretlen elérhetőségű ajánlat olcsóbb lenne, szaggatott keretes sárga cella jelzi („legolcsóbb, nem elérhető” / „legolcsóbb, elérhetőség ismeretlen”), és a „Legolcsóbb ajánlat” oszlop is kiírja az árát és a webshopot. Ilyenkor az Excel- és CSV-exportban is az elérhető ajánlat kapja a legolcsóbb jelölést.
- A webshopok paneljének tetején új **Mind keresésben** pipa: egy kattintással kijelölheted vagy kiveheted a fül összes webshopját.
- Vos Truckparts: a webshop csak a raktáron lévő alkatrészeket listázza, ezért minden megtalált alkatrész „Készleten” jelzést kap. A darabszámot és a szállítási határidőt a webshop nem adja meg, ezek továbbra is ismeretlenek.

## 2026-09-24-1033 — 2026-09-24

- EUTruckParts: a keresés közvetlenül a találati oldalon indul, és tovább vár a lassan válaszoló webshopra, így elkerüli a kezdőoldal betöltésénél tapasztalt időtúllépést.
- Inter Cars és HIFI FILTER: a kártyáikon már elmenthető a felhasználónév és a jelszó. A Norma a mentett adatokkal bejelentkezik; az Inter Cars kétlépcsős belépését is kezeli. A Cloudflare emberi ellenőrzését továbbra is kézzel kell elvégezni.
- Bárdi Auto: javítottuk az automatikus bejelentkezést, hogy a Norma a rejtett belépési panelt is megnyissa a mentett adatok kitöltése előtt.
- Auto Brand: lejárt munkamenetnél a Norma a mentett adatokkal újra bejelentkezik, és folytatja az összehasonlítást. Javítottuk a sikeres belépés után jelentkező téves „bejelentkezés szükséges” leállást.
- HIFI FILTER: a kártya a többi webshopéval azonos kezelőelemeket használ; eltávolítottuk a külön emberi ellenőrzés gombot. A sikeres bejelentkezés-ellenőrzés után már nem marad tévesen „Bejelentkezés szükséges” állapotban.
- Új versenytárs: **HIFI FILTER**. A kártyáján nyisd meg a bejelentkezést, és a webshop ablakában lépj be; az esetleges Cloudflare-ellenőrzést is ott végezd el. A keresés a saját nettó árakat, az elérhetőség jelzését és a HIFI által megadott megfelelőket olvassa. Ugyanaz a szűrő több gyártói hivatkozás esetén is csak egyszer jelenik meg.
- Új versenytárs: **Inter Cars**. A kártyáján nyisd meg a bejelentkezést, és a webshop ablakában lépj be; az esetleges Cloudflare-ellenőrzést is ott végezd el. A keresés látható böngészőablakban fut, a saját nettó és bruttó árakat, készletet és az Inter Cars által jelölt OEM megfelelőket olvassa.
- Auto Brand: a raktáron lévő alkatrész mostantól „Ma” elérhetőként és a készlet mennyiségével jelenik meg (melyik raktárban hány darab van). Eddig tévesen a szállítási időt mutattuk (például 14 nap), akkor is, ha az Auto Brand raktárában volt belőle.
- A webshopok két fülre kerültek az oldal tetején: **Versenytársak** és **Beszállítók**. Az Opoltrans mostantól a Beszállítók között van. Mindig a nyitott fül webshopjainál keresünk, és mindkét fülnek saját előzménye van: a korábbi összehasonlítások a Versenytársak fülön maradnak, a Beszállítók fül üresen indul. A Norma megjegyzi, melyik fül volt utoljára nyitva.
- Új versenytárs: **Unix Auto**. A kártyáján add meg a belépési adataidat (partnerkód vagy e-mail és jelszó), utána az összehasonlítás a Unix Auto árait is lekéri.
- Új versenytárs: **Elit**. A kártyáján add meg a belépési adataidat, utána az összehasonlítás az Elit árait is lekéri. Az Elit maga jelzi, ha egy termék a keresett kód megfelelője, ezért ezek „OEM megfelelő” jelölést kapnak.
- Új versenytárs: **Jarex** (szűrők). A kártyáján add meg a belépési adataidat. A kék (kedvezményes) árat hasonlítjuk össze, nettóként; a szürke, áthúzott ár eredeti árként látszik. A Jarex által egy eredeti kódhoz sorolt termékek „OEM megfelelő” jelölést kapnak.
- Új, első helyen álló webshop: **EUTruckParts**. Nyilvános árak, bejelentkezés nélkül. Termékenként minden vásárlási lehetőség megjelenik: a saját készletről („Ma”) és a beszállítótól rendelhető („Pár nap”) is, a saját ára szerint.
- Új versenytárs: **Vos Truckparts** (DAF, Scania és Volvo teherautó-alkatrészek, új és használt, euróban). Ehhez nem kell bejelentkezni: a nyilvános webshopból olvassuk az árakat, a kártyáján ezért nincs belépés. A használt alkatrészeket „(használt)” jelöli.
- A kinyitott találatoknál minden ajánlat kártyáján a versenytárs neve mellett ott a logója is, így első ránézésre látszik, kié az ajánlat.

## 2026-09-23-0942 — 2026-09-23

- update news modal

## 2026-09-23-0919 — 2026-09-23

- A versenytárs kártyája rövidebb lett: az ellenőrzött bejelentkezésnél már csak a jelvény látszik, a hosszú magyarázó szöveg nélkül. Ha tennivaló van (nincs bejelentkezve, hiba, nyitva a bejelentkező ablak), a magyarázat továbbra is ott marad.
- Mindegyik versenytárs kártyáján megadhatod a belépési adataidat. Mentés után a mezők eltűnnek, és csak rövidített adatok látszanak (például `of***************ro` és `n**********************1`), hogy felismerd, melyik fiók és melyik jelszó van elmentve. Minden csillag egy rejtett karakter. A Norma titkosítva, csak ezen a gépen tárolja őket, a jelszót soha nem mutatja vissza, és ha lejár a munkamenet, magától bejelentkezik – a keresés nem szakad félbe.
- Ha a versenytárs nem fogadja el a mentett jelszót, a Norma nem próbálkozik újra vele, hanem szól, hogy frissítsd. Így nem zárolják a fiókodat. Az „Újra megpróbálom” gombbal újra engedélyezheted, ha közben rendbe jött.
- Új versenytárs: **Dubhe**.
- Új versenytárs: **Auto Brand**. A kártyáján jelentkezz be egyszer; a keresés saját böngészőablakban fut, ezért ilyenkor megjelenik egy ablak.
- Új versenytárs: **Materom**. A kártyáján jelentkezz be egyszer, utána az összehasonlítás a Materom árait is lekéri.
- Az összehasonlítás csak akkor indítható, ha minden kijelölt versenytársnál van mentett bejelentkezés; a gomb addig inaktív, és kiírja, hol kell még bejelentkezni. Így nem megy el felesleges futással az idő.
- A bejelentkezésre váró versenytárs kártyája most pirossal kiemelve látszik, „Bejelentkezés szükséges” felirattal.
- Az „Összehasonlítás indítása” gomb futás közben „Keresés leállítása” gombbá változik, így ugyanott állítható le, ahol elindult. Külön leállító gomb már nincs.
- Ha menet közben derül ki, hogy egy versenytárs bejelentkezése lejárt, a Norma azonnal leállítja az egész keresést, és megírja, melyik versenytársnál kell újra bejelentkezni. A addig lekért eredmények megmaradnak.
- Az ár nélküli találatok (katalógustételek, „ár kérésre” sorok) már nem jelennek meg sem a táblázatban, sem az Excel- és CSV-exportban.
- A Materomnál egy alkatrészhez több szállítási lehetőség is tartozhat (különböző raktár, ár és határidő); a keresett cikkszámnál mindegyik megjelenik, így a legolcsóbb és a leghamarabb érkező is látszik.

## 2026-09-21-1415 — 2026-09-21

- update whats new

## 2026-09-21-1403 — 2026-09-21

- Frissítés után rövid összefoglalót mutat a Norma arról, mi változott.
- A korábbi „beszállító” megnevezés helyett mindenhol „versenytárs” szerepel.
- A fejlécben megjelenő **Frissítés** gombbal azonnal telepíthető az új kiadás; ha valaki éppen dolgozik a Normában, nem indul újra magától.
- A találati táblázat sorai megint egy vonalban vannak.

## 2026-09-21-1350 — 2026-09-21

- update release naming
- use competitor term instead of supplier

## 2026-09-21 — 2026-09-21

- fix release and publish

