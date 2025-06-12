## Description ##

Ce site est construit avec *Github Pages*. À chaque modification d'un ou plusieurs fichier, le site est compiler en un format statique et télécharger sur le web. Les pages sont en format *Markdown* (.md), *HTML* (.html). La plateforme utilisée pour interpréter les fichiers est *Jekyll*.

## Ajouter une démonstration ##

1. Aller dans le dossier `_demos`, cliquer sur un fichier existant et copier le contenu.
2. Retourner dans le dossier `_demos`, cliquer sur `Add File` -> `Create file`.
3. Coller le contenu du fichier existant et modifier le pour la nouvelle démonstration
4. Sauver en cliquant sur `Commit changes...` et suivant les instructions.
5. Le site web prendra quelques minutes pour compiler une fois le fichier sauvé.

## Ajouter une image ##

1. Aller dans le dossier `assets/images/fullsize`
2. Cliquer sur `Add file` -> Upload Files` et télécharger les images.
3. Les images peuvent maintenant être utlisées avec leur nom (sans les noms de dossiers) avec le taq `{% picture filename.jpg %}` en remplaçant `filename.jpg` avec le nom de fichier approprié.
