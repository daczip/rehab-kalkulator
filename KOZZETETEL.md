# Közzététel GitHub Pagesen – lépésről lépésre

Nem kell programozni és git-et telepíteni: minden a böngészőben elvégezhető, kb. 10 perc.

## 1. GitHub-fiók
Ha még nincs, regisztrálj a https://github.com/signup oldalon. A választott **felhasználónév** része lesz a kalkulátor webcímének (`daczip` → `https://daczip.github.io/...`).

## 2. A webcím a fájlban
**Kész:** az `index.html` és a `README.md` már a `daczip` felhasználónévvel készült. A kalkulátor címe: https://daczip.github.io/rehab-kalkulator/

> Fontos: a repó neve pontosan `rehab-kalkulator` legyen, különben a webcím és a LinkedIn-előnézet nem fog egyezni.

## 3. Repó létrehozása
1. Jobb felül **+** → **New repository**.
2. **Repository name:** `rehab-kalkulator`
3. **Public** (a GitHub Pages ingyenes fióknál csak nyilvános repóval működik).
4. Ne pipáld be a README hozzáadását. → **Create repository**.

## 4. Fájlok feltöltése
1. Az üres repó oldalán kattints: **uploading an existing file**.
2. Húzd be a kicsomagolt mappa **tartalmát**: `index.html`, `og-image.png`, `README.md`, `LICENSE`, `KOZZETETEL.md`.
3. A `.nojekyll` rejtett fájl, a fájlkezelő alapból nem mutatja. Ha nem látod, nem baj – egyetlen fájlból álló oldalnál nem szükséges.
4. Lent **Commit changes**.

## 5. GitHub Pages bekapcsolása
1. A repóban: **Settings** → bal oldalt **Pages**.
2. **Source:** *Deploy from a branch*
3. **Branch:** `main`, mappa: `/ (root)` → **Save**.
4. 1–3 perc múlva a lap tetején megjelenik: *Your site is live at https://daczip.github.io/rehab-kalkulator/*

## 6. Ellenőrzés
- Nyisd meg a címet számítógépen és telefonon is.
- A böngésző címsorában nézd meg: `.../og-image.png` – meg kell jelennie az előnézeti képnek.

## 7. LinkedIn-előnézet frissítése
A LinkedIn az első megosztáskor eltárolja az előnézetet. Mielőtt posztolsz:
1. Nyisd meg: https://www.linkedin.com/post-inspector/
2. Illeszd be a kalkulátor címét → **Inspect**.
3. Ellenőrizd a képet, címet és leírást. Ha javítasz az oldalon, itt újra lekérheted.

Ezután a linket bármelyik bejegyzésbe beillesztheted; a kép és a cím automatikusan megjelenik. Ha a bejegyzéshez saját képet is csatolsz, a LinkedIn azt mutatja a link előnézete helyett – ilyenkor a linket a szöveg első sorába érdemes tenni.

## Módosítás később
A repóban kattints az `index.html`-re → ceruza ikon (**Edit**) → módosítás → **Commit changes**. Az oldal 1–2 percen belül frissül.

## Saját domain (opcionális)
Ha van saját domained (pl. a szakértői honlapodé), a **Settings → Pages → Custom domain** mezőben beállítható. Ilyenkor az `index.html`-ben az `og:url` és `og:image` címet is a saját domainre kell átírni.
