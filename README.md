# MobilalkHorgaszShop
Mobilalkalmazás Fejlesztés Horgászbolt App
  Orosz Bence
  LGI301

1. A forráskód a master branchen elérhető -> app/src/main. Külön mappában vannak a classok/activityk és az xml/drawable fileok de mindent meg lehet találni a main mappán belül.
2. Firebase adatbázist használ az app, ami async módon olvas, létrehoz, töröl adatokat, viszont hogy véletlen se lépjem túl a fizetős korlátokat lekorlátoztam 3 post-ra (3 külön "megvehető" árura). Ezeket bejelentkezés / anonym belépés után ki lehet törölni az adatbázisból vagy újra létre lehet hozni ezt a hármat. 
3. Lehet regisztrálni, bejelentkezni regisztrált és anonym módon is.
4. Lehet kosárba rakni a feltüntetett árucikket és akkor megnő a "népszerűsége" és ez lesz a lista tetején. Ha törlünk árucikket az adatbázisból akkor megváltozik a sorrend a képek id-ja szerint viszont a jobb felső "rendezés újra" gomb segítségével ismét rendezhetünk ami random vagy növekvő vagy csökkenő sorrendben a kosárbatétel száma szerint rendez. Válthatunk nézetet is a felső grid iconra nyomva. 
