# 🗝️ Labyrinthe — ChadGangGames

Le classique jeu de plateau où le labyrinthe bouge à chaque tour, version web pour le hub ChadGangGames.

- **En ligne** (2 à 4 joueurs + spectateurs) via le SDK du hub : `ChadGang.join`, état complet versionné envoyé avec `keep`.
- **Même écran** ou **contre des bots** 🤖 quand le jeu est ouvert hors du hub.
- Effets : tuiles qui coulissent, tremblements, particules, bannières, feux d'artifice, sons synthétisés (bouton pour couper).

Tout le jeu tient dans `index.html` (aucun build). `chadgang.json` + `cover.png` = la fiche du jeu dans le hub.

Pour tester en local : ouvrir `index.html` dans un navigateur (mode même écran / bots).
