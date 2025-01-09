# Modèle de projet SASS

/!\ En mobile first
Avec un index contenant des cartes qui sont des liens vers des pages enfants (ici la meme page template répétée)

## Pour lancer le projet

- ouvrir un terminal à la racine du projet
- lancer la commande sass .\SASS\main.scss .\public\main.css
  La commande compile le fichier main.scss et produit en sortie le fichier main.css qui est appelé dans les différents fichiers html

- Ouvrir le fichier index.html dans un navigateur

## Structure

- le dossier public contient le fichier main.css de destination (généré en sortie de la compilation sass)
- le dossier child pages contient les pages html reliées à l'index
- le dossier assets contient les images et textes utilisés dans le pages enfants
- le dossier SASS est structuré en suivant le pattern 7.1
