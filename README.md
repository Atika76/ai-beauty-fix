# AI Beauty Fix

Ez a repository egy GitHub Pages-kompatibilis demo weboldalt tartalmaz az *AI Beauty Fix* fotó-retusáló szolgáltatáshoz.

## Tartalom
- `index.html` – a teljes, single-file frontend demó (feltöltés, ingyenes retus 3/nap vízjellel, kredit csomagok és előfizetések PayPal gombokkal).
- `README.md` – ez a fájl.
- `LICENSE` – MIT licenc.

## Mit kell tenned a telepítéshez
1. Hozz létre egy új GitHub repository-t, például `ai-beauty-fix`.
2. Tedd fel a fájlokat (index.html, README.md, LICENSE).
3. A repo beállításokban engedélyezd a **GitHub Pages**-t: Branch: `main`, Folder: `/ (root)`.
4. Nyisd meg a Pages URL-t (pl. `https://your-username.github.io/ai-beauty-fix/`).

> A PayPal gombok return/cancel URL-jei dinamikusan beállítódnak, így működni fognak a GitHub Pages URL-eddel.

## Fontos a valódi használathoz
- **Szerver-oldali hitelesítés szükséges**: PayPal IPN / Webhooks / REST API segítségével ellenőrizd a tranzakciókat, mielőtt krediteket jóváírnál.
- **Valódi AI feldolgozás** jelenleg nincs; a `index.html` kliens-oldalon szimulálja a retusálást. Tervezzünk egy szerver-oldali API-t (pl. Node.js + AI), ami feldolgozza a képeket.
