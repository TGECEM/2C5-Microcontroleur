---
title: Chapitre 1
description: Introduction à Git
---

# Chapitre 1 - Introduction à Git
## :question: Pourquoi l'utiliser ?
Si l'utilisation de Git ajoute des étapes, pourquoi pratiquement tous les professionnels qui programment utilisent des **gestionnaires de révision**?
1. Pour garder un **historique** des versions
2. Pour **collaborer** efficacement
3. Pour **réparer** des erreurs

## :school: GitHub Classroom
Pour vous habituer à utiliser des gestionnaires de révisions, nous utiliserons GitHub Classroom pour ce cours. Dans l'écosystème, voici ce que nous utiliserons :
- Git
  - Tortoire Git
  - GitHub
    - GitHub Classroom
   
## :ballot_box_with_check: Accepter un travail GitHub Classroom
- Vous devez vous créer un compte **GitHub**, vous l'utiliserez pendant toute la session.
- Connectez-vous au PC du laboratoire avec **votre compte TGE** pour que votre compte GitHub ne soit configuré **que** sur votre compte sur le PC.
- Configurez votre compte GitHub en cliquant droit dans le navigateur de fichier et en ouvrant **Tortoise Git** --> **Settings**, puis en configurant le compte dans l'onglet **Git**

::tip
Sur les PCs Windows, il faut souvent cliquer sur **Afficher plus d'options** afin de voir les options apparaître.
::

- Avant chaque laboratoire, vous recevrez une **invitation** pour accepter le travail.
- En acceptant le travail, votre serveur de travail (*repo*) sera créé (ex : https://github.com/TGE-243-2C5/laboratoire-1-antoinebsimard)

## :busts_in_silhouette: Cloner son répertoire
Dans votre répertoire de travail **local** (ex: C:\Users\antoine\Documents\Atmel Studio\7.0), cliquer droit et sélectionner **Git Clone**

::tip
Encore une fois, il est possible de devoir cliquer sur **Afficher plus d'options** selon le système d'exploitation
::

Dans la fenêtre pop-up, entrer l'URL de votre *repo* GitHub Classroom.

Votre répertoire de travail **local** sera créé.

## :runner: Actions de base
Votre répertoire contiendra les fichiers de départ (en anglais *starter code*) et vous y ajouterez ou modifierez le contenu en créant des *commits*. Les actions que vous aurez le plus souvent besoin pour ce cours sont :

- **Clone** : permet de cloner la configuration et le contenu du serveur dans un répertoire local (i.e. : sur le PC)
- **Commit** : permet de préparer une nouvelle version (un *commit*) à trasmettre au serveur
- **Push** : permet de transmettre le(s) nouveau(x) *commit(s)* au serveur
- **Show Log** : permet d'afficher l'historique des *commits*
- **Pull** : permet de récupérer du serveur les dernières versions
- **Diff** : permet d'afficher les modifications locales
- **Revert** : annule les modifications locales

## :thumbsup: Bonnes pratiques
On cherche autant que possible que l'historique soit **linéaire** sans modifications (branches) qui partent dans tous les sens. Généralement, **plus** il y a de *commits*, **mieux** c'est (certaines conditions s'appliquent). À chaque commit, on doit inscrire une description de la modification (**Message**), on veut être aussi **explicite** que possible.
