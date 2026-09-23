# Logemi — site vitrine

Site one-page animé (scroll scrubé, scènes épinglées, zoom-texte, rideau de
lames, traînée souris), généré depuis le template « Site Immersif ».

## Lancer en local

```bash
node .claude/serve-logemi.mjs
# → http://localhost:4385
```

## Structure

| Fichier | Rôle |
|---|---|
| `index.html` | Squelette des scènes — **ne pas modifier** |
| `app.js` | Moteur d'animation — **ne pas modifier** |
| `styles.css` | Feuille pilotée par tokens. Seul l'accent (`--lime`, `--lime-ink`) a été changé |
| `content.js` | **Tout le contenu éditorial.** Moitié haute uniquement ; la moitié « INJECTION » ne se touche pas |
| `images/` | Visuels du site (domaine public — voir `images/CREDITS.json`) |
| `illustrations/` | 4 illustrations SVG de la grille bento |

## Thème

Sombre (`<html data-theme="dark">`), accent bleu `#5b9dff` — version éclaircie
du bleu de marque `#0a59e4` pour rester lisible sur fond sombre.
