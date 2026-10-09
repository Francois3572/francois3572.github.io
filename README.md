# Francois3572.github.io

Site public des apps — servi par GitHub Pages à la racine du domaine
`francois3572.github.io`.

## ⚠️ Les pages légales ne s'éditent pas ici

`dicerollcalculator/legal/fr/**` et `.../en/**` sont **générés** (la page
`legal/index.md`, elle, s'écrit ici). La source de vérité est le dossier
`legal/` du dépôt de l'app, et l'export se fait depuis là :

```
cd ~/Developer/Projets/DiceRollCalculator
python3 scripts/export-legal.py
```

Éditer une page ici serait écrasé au prochain export — et le texte de
référence, celui qui fait foi juridiquement, resterait inchangé.

## Ce qui s'édite ici

- `index.md`, `<app>/index.md` et `<app>/legal/index.md` — pages d'accueil et choix de langue ;
- `_layouts/` et `assets/style.css` — mise en page, sans thème Jekyll ;
- `_config.yml`.

## Ajouter une app

Créer `<app>/index.md` (permalien explicite), puis ajouter la table
`DOCUMENTS` correspondante dans le script d'export du dépôt de cette app.
Les permaliens ne doivent **jamais** changer une fois publiés : ils partent
dans les fiches store et dans les consoles publicitaires.
