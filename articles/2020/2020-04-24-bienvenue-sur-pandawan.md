---
date: 2020-04-24 
title: "Bienvenue sur pandawan" 
author: 
    name: Tai LE
    avatar: "https://avatars3.githubusercontent.com/u/17015240?s=460&u=3a5597dca84d3eadea42c5433d80ab44847999b6&v=4"
    description: "Enjoy life"
    link: "https://github.com/taiwabisabi"
tags:
	- news
---

# Qu'est ce que Pandawan ?  
Pandawan est un blog sur le **développement web**.
L'idée de pandawan est de proposé des articles de la communauté web depuis des fichiers markdown réunie sur un seul et même repo.
Afin que chacun d'entre-nous puisse consulter, sauvegarder et/ou créer des artcles à votre guise.

## Comment contribuer ?
C'est très simple, il vous suffit de suivre les étapes suivantes :
* Créer un fork du projet sur Github (cf. [repo](https://github.com/taiwabisabi/pandawan_articles/))
* Faire un clone de votre fork sur votre machine | `git clone <fork_repo>`
* Mettre ce repo Github en remote `origin` | `git remote origin <fork_repo>`
* Mettre le repo original en remote `upstream` | `git remote upstream https://github.com/taiwabisabi/pandawan_articles`
* Créer un nouvelle branche depuis master | `git checkout branch <article>`
* Créer votre nouvelle article dans le bon dossier | `Suivre les instructions du readme.md`
* Faire un commit de votre changement | `git commit -m 'Nouvel article'`
* Faite un rebase de master | `git rebase upstream/master`
* Faite un push de votre branch sur la remote origin | `git push origin <article>`
* Depuis votre fork faire un pull request sur la branch staging

## Comment écrire un article ?
C'est tout aussi simple, vous devez récupérer [le fichier sample](https://github.com/taiwabisabi/pandawan_articles/blob/staging/YYYY-MM-DD-sample.md).

Il vous suffira de bien renseignez l'en-tête qui se présente comme ceci
```md
date: YYYY-MM-DD 
title: "Votre Titre" 
author: 
    name: Votre Nom
    avatar: "Lien de votre image avatar"
    description: "Citation ou Description de vous"
    link: "Lien pour votre profil"
tags: 
    - tag1
    - tag1
```

Ensuite écrivez votre article en utilisant la syntaxe MarkDown.
Mettez votre article dans le dossier de l'année en cour, et les images dans le dossier `images` associé.

![voila](https://media.giphy.com/media/8P1oO2JbrZK2uSYnL6/giphy.gif)

---

> Le blog est propulsé par Gatsby 
> ![Gatsby Logo](./images/gatsby_logo.png)