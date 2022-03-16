---
title : Home Assistant - Guide du développeur # Titre article explicite
date: 2022-03-03 # Date format YYYY-MM-DD
lastmod:   # Date format YYYY-MM-DD   SI rine n'est rentré il prendra la modification GIT.
draft: false
#layout: pages 
type: guidedev # Types existant : pages; news; awesome; guidedev; etc. Laisser vide pour les articles

description: "Ce guide permet de vous familiariser avec le developpement sur Home Assistant. Il a était mis en place par la communauté Francophone autour de Home Assistant dans le but d'avoir un guide en francais et un lieu de developpement francophone. Il se veut evolutif et participatif. " # Description du sujet.
# hero: /path/image.ext # Recherche un fichier hero.(webp;jpg;png;svg) a la racine du dossier OU si un hero est defini ici SINON il prend un hero par defaut.

author:

#socialshare: true # Active l'option de partage
article_ha: false # Ajoute les boutton du forum et les medias des deux communautés Home Assistant (Off et HACF)

hacf:      # Liens vers le post du forum HACF.
url_off:   # Liens vers le post du forum Officiel.


categories: # Categories atuelles : domotique; home assistant; news; nodered;....

series: # En cours permet de reunir des series d'articles autour d'un meme sujet (ex : bien debuter avec HA; ou les addons essentiels pour commencer).
- guide
  
tags: # Mettre ce qui est en relation avec l'article NE PAS REMETTRE les categories.
- developpeur

keywords: # Mettre tous les mots definissant votre article, ils sont utilisés pour le referencement. PAS de limitation.
- guide
- developpeur
- home assistant
- hacf
- communauté francophone

##################################################
##################################################

# Toutes ne sont pas a remplir (ex : pour les pages), il suffit pour cela de ne rien  mettre apres les : ou alors de commenter la ligne avec un # devant.

##################################################
##################################################

###################
# Non fonctionnel
###################
#author:
#  name: Pulpy
#  image: /images/author/pulpy.jpeg

#menu:
#  sidebar:
#    name: HA 2021.9.X
#    identifier: ha-2021-9-X
#    parent: news-home-assistant
#    weight: 10
---
## Présentation

Ce guide a pour vocation de présenter le développement de composants de Home Assistant.

Pour ce faire nous présenterons indépendamment chacun des environnements de développement :

- le backend qui concerne les intégrations (entités/sensors)

- le frontend qui concerne l'interface utilisateur (Lovelace et ses composants)

## La boîte à outils

Chaque environnement a ses outils spécifiques et seront précisés dans chaque section.

Néanmoins voici quelques éléments commun aux deux :

**Obligatoires**:

- [git](https://git-scm.com/book/fr/v2) pour la gestion de version.
- Un compte [Github](https://github.com/)

**Recommandés**:

- [Docker](https://www.docker.com/) pour tester vos contributions dans un environement local et dédié (conteneur).
- [Visual Studio Code (VSC)](https://code.visualstudio.com/). Tout autre editeur peut convenir.
  VSC offre plusieurs addons qui facilitent le développemnent avec Home Assistant.
- L'Addon [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) pour VSC.
  Il permet d'utiliser les conteneurs de développement via Docker.

## Participer aux projets

Avant de présenter plus en avant le développement sous Home Assistant, nous allons faire un point sur la gestion d'un projet (un développement).

Si vous êtes familier avec GitHub, vous pouvez passer ce chapitre. Pour les autres ...

- [Travailler avec GitHub](github)

## Les environnements

Il y a deux environnements distincts :

- Le backend ou le coeur de Home Assistant
- Le frontend ou l'interface utilisateur

Suivant ce que vous allez travailler, vous n'aurez pas besoin des mêmes langages, compétences et ressources.

- [Développer en backend](backend)

- [Développer en frontend](frontend)

## Les ressources

Ci-dessous un ensemble de ressources qui compléteront votre apprentissage.

- La [documentation développeur](https://developers.home-assistant.io/) chez Home Assistant
- La gestion des [flux](https://guides.github.com/introduction/flow/), des [Issues](https://guides.github.com/features/issues/) et des [Pull Request](https://guides.github.com/activities/forking/) (PR) de Github
- Le template prêt à lemploi [CookieCutter](https://github.com/oncleben31/cookiecutter-homeassistant-custom-component)
- Les icônes incontournables de [Material Design](https://materialdesignicons.com/)
