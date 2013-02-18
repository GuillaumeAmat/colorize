# Colorize

Script Python permettant de colorer des sorties standards, des fichiers textes, etc.


## Utilisation

Usage: colorize [OPTIONS] [MOT_CLEF_1 MOT_CLEF_2...]

Options:
  -h, --help          Affiche cette aide et termine le programme
  -c, --clean-screen  Nettoie l'ecran avant d'afficher la sortie
  -i, --ignore-case   Rend la coloration insensible a la casse


## Exemple

`$ tail -f /var/log/httpd/error.log | colorize mot_clef_1 mot_clef_2 "[0-9]"`

`$ cat mon_fichier.txt | colorize -ci "mot clef avec des espaces"`
