# Fusion 2026 — repository corretto completo

Questo pacchetto corregge la versione precedente includendo più materiale del file SplitFusion e una pagina di controllo contenuti.

## Render

```bash
rm -rf docs
quarto render
xdg-open docs/index.html
```

## Verifiche

```bash
grep -i "reveal" docs/index.html | head
find docs/originali docs/downloads -maxdepth 2 -type f | sort
```

## Push

```bash
git add .
git commit -m "Complete Fusion 2026 material"
git push origin main
```
