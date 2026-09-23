# Norma changelog

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

