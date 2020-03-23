# Cours-git

Ce fichier est écrit en [Markdown](https://fr.wikipedia.org/wiki/Markdown). Du coup, pour le lire correctement clique sur [ce lien](https://github.com/jojomon42153/cours-git)

Cours git signes et formations

!!! Pro tip: Git, c'est sombre et mystique au début, c'est pourquoi il est fortement recommandé de vous en servir pour TOUS vos prochains projets, surtout ceux qui se réalisent en équipe, afin que git devienne naturel chez vous. Par exemple, je m'en sers moi-même pour noter, ranger, classer tous les cours/conférences que je suis ammené à suivre pendant mes formations. POURQUOI s'embêter avec ca? Car avec de la pratique, utiliser cet outil sera comme respirer pour vous, et un pro git est très souvent apprécié en entreprise (vu que ca parraît sombre, mystérieux et magique pour ceux qui ne savent pas l'utiliser). !!!

## GIT ? C'est quoi ?

Créé par l'éminent Linus Torvalds, git est un gestionnaire de version, c'est à dire qu'il permet entre autres de gérer l'ajout de nouvelles features sur un projet sans qu'il n'y ait de conflit entre les différentes versions.

En effet, imaginez-vous en train de travailler sur un projet en même temps que toute une équipe;
Si des modifications sont faites par plusieurs personnes sur le même fichier, sans git, il faudrait passer un temps fou pour toutes les fusionner, et en cas de bug ce serait l'enfer pour revenir a une version stable.

De plus, git est la base du logiciel libre: le logiciel libre est le partage de codes sources sur des plateformes git telles que github, gitlab ou bitbucket, permettant a tout le monde de pouvoir collaborer librement à un projet même sans en connaître les auteurs). C'est un réel réseau social des dévelopeurs.

Pour un développeur débutant cherchant un travail, il peut aussi être intéressant d'avoir un github recensant les projets qu'il a réalisé, comme un portfolio de ses compétences.

Enfin, les gestionnaires de package tels que npm, brew, etc... fonctionnent avec git.

Bref, pour résumer, imaginez un bouton "sauvegarde" avant un boss de jeu vidéo, et imaginez que vous avez un nombre infini de slots de sauvegarde. Git, c'est ça.

## Sommaire

Nous utiliserons un mix entre la méthodologie 42 et un cours "normal"; vous devrez réaliser une série d'exercices dont les connaissances vous auront été expliquées brièvement à l'oral. Pour chaque exercice vous aurez aussi une base de connaissances dans ce fichier. Ainsi, vous pourrez garder ce cours et vous en servir comme une CheatSheet, et/ou refaire les exercices chez vous.

Ce cours sera décomposé en 4 grandes parties:

* partie1 **Add, Commit, Push**: Ici vous créerez votre premier repository et aprendrez a vous en servir de manière basique, en sauvegardant votre travail de manière régulière.

* partie2 **Le versionning**: Dans cette partie, vous apprendrez à naviguer entre les différentes versions de votre code.

* partie3 **Les branches**: Une nouvelle feature dans votre code? Ne cassez pas ce qui fonctionne déjà et développez votre feature en toute sécurité.

* partie4 **Les merge**: Fuuuuu-sion! Découvrez comment fusionner vos branches entre elles une fois que tout fonctionne.

Et enfin une **cheatsheet** dans laquelle vous irez piocher vos commandes pour les exercices.

Maintenant, fais la commande pour passer dans la branche partie1 et ainsi voir les modifications que j'ai apporté à ce fichier (wut? c'est quoiiii? omg je suis perdu! => lis plus bas, applique, tu comprendras en partie 3)

## Lexique des commandes

### Les branches

* `git checkout nom_de_ma_branche`: change de branche pour aller sur "nom_de_ma_branche"
