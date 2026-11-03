# BARVY-UNIMAX – redesign e-shopu (prototyp)

Klikací prototyp redesignu e-shopu barvy-laky-unimax.cz (BSSHOP).

## Spuštění
Prototyp potřebuje lokální server (kvůli načítání skriptů):

```
cd prototyp
python3 -m http.server 8000
```
a otevřít http://localhost:8000/index.html

## Sdílení jako web (GitHub Pages)
1. Na GitHubu: Settings → Pages → Source: „Deploy from a branch“, Branch: `main`, složka `/ (root)` → Save.
2. Za 1–2 minuty bude web na adrese `https://<účet>.github.io/barvy-unimax/`.

## Obsah
- `prototyp/index.html` – celý prototyp (homepage, kategorie, detail produktu, košík, účet, informační stránky)
- `prototyp/data.js` – ukázková data produktů a kategorií
- `prototyp/imgs-*.js`, `prototyp/img/` – obrázky
- `prototyp/support.js` – běhové prostředí prototypu (React)

## Poznámky pro vývoj
- Ceny, dostupnost, hodnocení, dotazy a „nejnižší cena za 30 dní“ jsou ukázkové – v e-shopu z feedu.
- CLP (bezpečnostní informace): struktura dat viz projektová dokumentace `clp-struktura-dat.md`.
- FAQ v kategoriích: doplnit strukturovaná data FAQPage.
- Piktogramy GHS nahradit oficiálními (UNECE).
