# WarWheel

Prototype jouable de la mécanique de roue : deux camps se battent à l'intérieur d'un immense anneau. Pousser le front fait tourner la roue, et le premier camp qui lui fait faire le nombre de tours fixé gagne.

## Jouer

Ouvrir `index.html` dans un navigateur, ou la version GitHub Pages du dépôt. Clavier et souris requis.

- `W` `A` `S` `D` : se déplacer, souris pour viser
- Clic maintenu : tirer, `R` : recharger
- `1` `2` `3` : carabine, précision, pompe
- `E` : poser un relais avancé quand la jauge est pleine
- `Échap` : pause

## Ce que le prototype teste

- Le front avance selon qui occupe la zone jaune.
- Les spawns restent toujours à 620 m derrière le front.
- Les relais soignent, tirent et servent de spawn, puis s'éteignent quand le front s'éloigne.
- Quatre secteurs : Corridors, Ravin, Plaine, Dépôt.

Tout le jeu tient dans un seul fichier HTML, sans dépendance.
