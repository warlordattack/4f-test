---
type: artist
author: 
date: 
title: 
notquotedlinks_internal:
notquotedlinks_external:
---

# Aide d'utilisation de l'éditeur de notice rédactionnelle dans Navigart3


## Introduction

* l'éditeur de notice rédactionnelles de Navigart3 permet de saisir le contenu de la notice au format Markdown
* il comporte dans son menu certaines fonctions mais pas toutes
* l'aide permet de retrouver la syntaxe des fonctions du menu mais aussi de trouver la syntaxe d'autres fonctions


## Les enrichissements typographiques
* **Pour avoir du texte en gras** : entourer le texte par ** ou __
* *Pour avoir du texte en italique* : entourer le texte par * ou _


## Les paragraphes

Pour faire un nouveau paragraphe, sauter une ligne

Premier paragraphe

Deuxième paragraphe   

Pour faire un simple retour à la ligne, mettre deux espaces en fin de ligne  
simple retour à la ligne

> Pour afficher un bloc de citation, commencez le paragraphe par un chevron fermant.   
> Si votre bloc contient plusieurs lignes, vous pouvez faire des sauts de lignes à la main et toutes les ouvrir par un chevron fermant, mais ce n’est pas nécessaire.
<!-- syntaxe pour séparer 2 blocs ; sans cela, ils fusionnent -->
> Pour afficher un bloc de citation, commencez le paragraphe par un chevron fermant.


## Insérer un filet
Pour afficher un filet de séparation, entrez au moins 3 signes moins - dans votre texte, sur une ligne entourée de sauts de lignes

---

## Faire une note en bas de page
Suite au mot ou à la phrase sur lequel porte la note, saisir le numéro de note au format [^1]  
A la fin de la notice rédactionnelle, saisir [^1]:
puis saisir un espace après le signe « : » et taper à la suite le texte de la note

## Insérer un lien externe
Saisir entre crochets le texte sur lequel on souhaite faire porter le lien, suivi de l’adresse du lien entre parenthèses.  
[texte du lien cliquable](http://adresse-du-lien-a-saisir-ou-coller)

## Faire des listes
Sauter une ligne avant le début de la liste.

Pour créer une liste non ordonnée :  

* item 1
* item 2
    * Sous élément avec au moins quatre espaces devant


Et une liste ordonnée :

1. item 1
2. item 2

## Faire des niveaux de titrage
Le titre principal est traité par les paramètres
on parle ici de titres dans le texte
Les titres sont créés avec un certain nombre de # avant le titre, qui correspondent au niveau de titre souhaité
### un titre de troisième niveau
#### un titre de quatrième niveau


# Colonnes


| Header 1      |     2 header    |   header 3 |
| ------------- |: -------------: | ---------: |
| 1 Online      |        1        |      value |
| Line 2        |        2        |      value |
| 3 Online      |        3        |      value |
