# Rehabilitációs hozzájárulás kalkulátor 2026–2027

**Mennyit fizet ma, és mennyit fizetne 2027-től?**

Ingyenes, böngészőben futó kalkulátor munkáltatóknak. Összeveti a rehabilitációs hozzájárulást a 2026-ban hatályos és a 2027-re tervezett szabályok szerint (T/927. számú törvényjavaslat), és megmutatja, hogyan alakul a költség és a megtakarítás megváltozott munkaképességű munkatársak foglalkoztatásával.

👉 **Élő változat:** https://daczip.github.io/rehab-kalkulator/

## Mit tud?

- **Hozzájárulás** – kötelező foglalkoztatási szint, beszámított és hiányzó létszám, a 2026-os és a 2027-es éves befizetés, sávhatár-figyelmeztetés, grafikon a létszám függvényében.
- **Foglalkoztatás költsége** – egy mondatban és két összevetett dobozban: mennyit fizet a munkáltató, ha nem foglalkoztat, és mennyit, ha igen; havi bontás egy munkatársra; részletes számítás a jelenlegi helyzettől a tervezett felvételig.
- **Tudnivalók és módszertan** – a változások összefoglalója, képletek, egyszerűsítések, források.

## A számítás alapjai

| | 2026 – hatályos | 2027 – T/927 szerint |
|---|---|---|
| Kötelező foglalkoztatási szint | a létszám 5%-a, 25 fő felett | változatlan |
| Mérték (hiányzó főnként, évente) | minimálbér 9× | 9× (25–249 fő), 11× (250–499), 13× (500–999), 15× (legalább 1000 fő) |
| Kétszeres beszámítás | – | fogyatékossági támogatás / vakok személyi járadéka; gyermekvédelmi gondoskodásból kikerült SNI-s vagy fogyatékossággal élő fiatal |
| Munkahelyi rehabilitációs mentor | korlátig beszámít (1 / 4 / 8 / 10 / 12 fő) | változatlan |

Mindkét évet a 2026-os minimálbérrel (322 800 Ft) számolja, így a különbség csak a szabályváltozást mutatja.

Források: 2011. évi CXCI. törvény (Mmtv.) 22–24. §; 2018. évi LII. törvény (Szocho tv.) 13. §; NAV 94. információs füzet (2026); T/927. számú törvényjavaslat 110–112. §.

## Felépítés

Az egész alkalmazás egyetlen fájl (`index.html`): HTML, CSS, JavaScript és az illusztráció is benne van. Külső függőség csak az Inter betűtípus (Google Fonts); ha nem töltődik be, a rendszer betűtípusa jelenik meg.

```
index.html     – a kalkulátor
og-image.png   – megosztási előnézet (LinkedIn, Facebook) 1200×627
.nojekyll      – GitHub Pages: a fájlok változtatás nélküli kiszolgálása
LICENSE        – MIT licenc
```

## Frissítés

A jogszabályi paraméterek az `index.html` szkriptjének elején találhatók (`MINIMALBER`, `SZABALY`, `MENTOR`). Ha az elfogadott törvény eltér a javaslattól, ezeket kell módosítani.

## Felelősségkizárás

Az eredmények tájékoztató jellegűek, nem minősülnek adó- vagy jogi tanácsadásnak. A 2027-es számítás a benyújtott törvényjavaslaton alapul; az elfogadott jogszabály eltérhet.

## Szerző

Daczi Péter, foglalkozási rehabilitációs szakember · MIT licenc
