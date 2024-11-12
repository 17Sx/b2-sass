Ce projet utilise **Sass** pour la gestion des styles CSS. Le dossier `src/scss` contient les fichiers `.scss` qui sont compilés en `.css` dans le dossier `src/css`.

## Installation

Assurez-vous d'avoir **Node.js** installé. Ensuite, installez les dépendances.

Utilisation de Sass
Commande de Compilation
Pour compiler les fichiers Sass en CSS, utilisez la commande suivante :


npx sass style.scss style.css


Mode Watch
Vous pouvez également activer le mode watch pour que Sass surveille les modifications et compile automatiquement le fichier dès qu’il est modifié :


npx sass --watch style.scss style.css

j'ai egalement utiliser les mixins et les variables.
