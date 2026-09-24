# Norma changelog

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

