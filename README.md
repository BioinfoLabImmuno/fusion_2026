# Nuovo repository — MTB Framework & SplitFusion

Questo repository contiene solo i tre materiali forniti, adattati allo stile RevealJS della masterclass precedente.

## Render

```bash
rm -rf docs
quarto render
xdg-open docs/index.html
```

## GitHub

```bash
git add .
git commit -m "Initial MTB Framework SplitFusion course"
git push origin main
```

GitHub Pages:
- branch `gh-pages`
- folder `/ (root)`

## Struttura

- `index.qmd` — presentazione RevealJS
- `materiali.qmd` — download dei file originali
- `fonti.qmd` — provenienza dei contenuti
- `originali/` — i tre HTML forniti
- `downloads/` — ZIP dei materiali
- `.github/workflows/publish.yml` — deploy automatico
