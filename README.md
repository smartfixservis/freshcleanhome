# Fresh Clean Home — web stranica

Statični sajt (HTML/CSS/JS), spreman za GitHub Pages.

## Objava na GitHub Pages
1. Napravi novi repozitorij na GitHubu (npr. `fresh-clean-home`).
2. Uploaduj **sadržaj ovog foldera** (ne sam folder) u korijen repozitorija — `index.html` mora biti u korijenu.
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. Za par minuta sajt je na `https://<korisnik>.github.io/fresh-clean-home/`.

## Struktura
- `index.html` — početna stranica
- `usluge/` — 7 podstranica usluga + `usluge.css`
- slike (`.jpg`, `.png`) u korijenu

## Galerija „Naši radovi"
Slike sa terena se dodaju u `index.html`, u listu `RADOVI`:
```js
const RADOVI=[
  {img:'radovi/1.jpg', title:'Dubinsko pranje kauča'},
];
```
(slike staviti u folder `radovi/`).

## Vlastita domena (opcionalno)
U Settings → Pages → Custom domain upiši domenu i kod registra domene postavi DNS zapise prema GitHub uputstvu.
