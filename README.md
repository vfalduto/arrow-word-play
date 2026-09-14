# arrow-word-play

Grilles de mots fléchés jouables dans le navigateur. Le site est statique : un player (`index.html` + `assets/`) et un dossier `grids/`.

## Jouer

`https://vfalduto.github.io/arrow-word-play/#/<nom>` ouvre `grids/<nom>.arw`.

## Publier une grille

1. Dans Arrowword, exporter le projet (`.arw`).
2. Déposer le fichier dans `grids/` sous un nom en minuscules, chiffres et tirets : `grids/ma-grille.arw`.
3. Commiter, pousser. Le lien est `…/#/ma-grille`.

La partie en cours (lettres, chrono, règles) est sauvegardée dans le navigateur du joueur.

## Mettre à jour le player

Depuis le repo `arrow-word` : `just publish-play <chemin de ce clone>`, puis commiter ici.
