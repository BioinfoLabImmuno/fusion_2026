# Fusion 2026 — slide iniziali migliorate

Questa versione migliora la prima parte della presentazione e rende più chiaro il percorso:
dato molecolare → evidenza analitica → interpretazione → actionability → report.

## Aggiornamento

Copia questi file nel repository `fusion_2026`, poi:

```bash
rm -rf docs
quarto render
xdg-open docs/index.html
git add .
git commit -m "Improve Fusion 2026 opening slides and style"
git push origin main
```

## GitHub Pages

Deve restare impostato su:

- branch `gh-pages`
- folder `/ (root)`
