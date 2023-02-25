# Ping-Pong Pársorsoló alkalmazás LabVIEW-ban megírva.
A szoftver használati útmutatója.

## A program futtatásának menete
   1. Az alkalmazás mappáján belül a "csapatok.txt" fájlt módosítsa a csapatok aktuális felépítésének megfelelően.
   2. A 2 csapat tagjait láthatja ABC sorrendben a "A csapatok tagjai" felirat alatt.
   3. Nyomja meg a "Sorsolás" gombot a véletlenszerű párosításhoz.
   4. A kisorsolt párosítást láthatja a "Az összesorsolt párok" felirat alatt.
   5. Ezt a párosítást a "Felolvasás" gomb lenyomásával a gép automatikusan felolvassa, teljes mondatokban. A felolvasás megismételhető.
   6. A párosításokat utólag is megtekintheti, az alkalmazás mappáján belül a "Naplók" mappában a dátum_x.txt naplófájlban (amiben az x az épp aktuális napon keletkezett naplófájl sorszámát jelenti), ami tartalmazza a mentés időpontját másodpercre pontosan, és a párok neveit is.
   7. A naplófájlt a "Naplófájl megnyitása" gomb meg is jeleníti.
   8. Az "Olvass el fájl megnyitása" gombra kattintva megnyílik az "Olvass el!" fájl, ahol további információkat tudhat meg (ön most épp ezt olvassa).
   9. A program a "Leállítás" gomb megnyomására leáll.

## További fontos tudnivalók
   1. A `Módosítás` gomb: 
      Segítségével, ha a csapatokban nem lenne mindenkinek párja, akkor ennek a gombnak a segítségével megnyithatja, és módosíthatja a fájlt.
   2. Az `Újraolvasás` gomb: Segítségével ismét beolvashatja az előzőleg már beolvasott hibás, vagy módosított csapatokat tartalmazó fájlt.
      2.1. Az `Újraolvasás` gombot a sikeres módosítás érdekében csak a módosítandó fájl mentése után nyomja meg.
      2.2. Amennyiben a csapatok közül, még így se lenne mindenkinek párja, vagy más hiba fordulna elő, vagy módosítani akarja, akkor nyomja meg mégegyszer a módosítás, majd a `csapatok.txt` fájl mentése után ezt a gombot.
   3. A `Sorsolás` gomb:
      Megnyomására a gép véletlenszerűen párokba rendezi a 2 csapat tagjait.
   4. A `Felolvasás` gomb:
      a. Megnyomására a gép felolvassa az összesorsolt párokat. Megnyomására a gép felolvassa az összesorsolt párokat.
      b. Ha felolvasta a párokat, akkor mégegyszer felolvashattatja a programmal.
   5. A `Naplófájl megnyitása` gomb:
      A program megnyitja a keletkezett naplófájlt.
   6. A `Leállítás` gomb:
      6.1 A program a gomb megnyomására leáll.
      6.2 A program a hangok olvasása közben nem tud leállni, memóriaszemét keletkezésének elkerülése végett!
   7. Az `Olvass el fájl megnyitása` gomb:
      A gomb megnyomására megnyitja az `Olvass el!.txt` fájlt.

## **A program megfelelő működése érdekében**
   **_FIGYELEM!_**
   1. Kérem, hogy az alkalmazás könyvtárán belüli adatok mappában lévő fájlokat **ne törölje**, és a bennük lévő adatokat **ne módosítsa**!
   2. A **hang** mappán belüli adatokat **ne törölje**!
   3. A **subvi** mappán belül **ne módosítsa, vagy törölje** az állományokat!

## Egyéb tudnivalók
   1. Amennyiben az alap 8 becenévtől eltérő beceneveket is akar kimondatni a programmal, akkor a hang mappába másolja bele a becenevek hangfelvételét a! A fájl neve legyen `Becenév.wav`! Fontos, hogy a fájl neve **NAGYBETŰVEL** kezdődjön!
   2. Az elkezdett felolvasási folyamatot nem lehet megszakítani!

## Köszönet
   Köszönet Kajtár Gergőnek a Design, a Dokumentáció, és a Programrendezés területén végzett munkájáért, Kajtár Bencének a Hangokért és Vizi Tibor tanárúrnak az egész éves munkáért.
