# Tutoriel sur python et numpy

## Pré-requis logiciels

Ce tutoriel est basé sur des notebook jupyter, il requiert:
* une distribution scientifique de python, la plus répendue étant anaconda [lien](https://www.anaconda.com)
* [mac/linux] pour travailler sur les canevas proposés, il suffit ensuite de taper:
  jupyter-notebook <fichier.ipynb> 
* [windows] naviguer dans anaconda pour charger le fichier
* [online] en cas de problème, les liens ci-dessous donne accès aux mêmes TP en ligne via google colab
  * il faut un compte gmail et une connexion internet pour en profiter
* [option avancée] éventuellement un éditeur avancé capable de gérer les notebooks: VS Code [lien](https://code.visualstudio.com)
VS Code est très bien fait: à l'ouverture des fichiers, en fonction des extensions, il propose de télécharger des plugins pour gérer les spécificités desdits fichiers.

## Déroulement de la session

### 1. Prise en main de python et des notebooks 
- Attention, c'est assez *contemplatif* (presque tout le code est donné)
  -  ne vous laissez pas étourdir par les notebooks qui *avancent tout seuls*: cherchez toujours à comprendre ce qui se passe
  - ajouter des boites, ajouter du code: vous pouvez tout modifier et même tout détruire, il suffit de re-télécharger le fichier en cas de problème.
- Il faut adapter sa vitesse: on veut passer vite sur ces pré-requis mais il faut quand même maîtriser python...
  - N'hésitez pas à sauter des exercices lorsque ça vous parait trivial: on peut toujours revenir en arrière!
- Posez vos questions au fur et à mesure

### 2. Numpy et matplotlib : l'**objectif central** de ces séances

Il s'agit d'une introduction à la programmation scientifique à travaers des exercices avancés sur numpy/matplotlib. 
De nouveau, l'enjeu est d'avancer à un bon rythme:

- Ne pas se laisser endormir par les boites déjà complétées, ajouter des boites et du code pour bien comprendre les fonctions, leur syntaxe et leur fonctionnement.
- Sauter les exercices triviaux ou trop scolaires pour vous: si vous êtes à l'aise, c'est intéressant d'aller directent aux parties 3/4
- NE PAS sauter ces exercices si vous vous sentez plus léger en python: le coeur de la séance se trouve bien ici!

### 3. Classification Bayesienne

On consolide la pratique du python scientifique à travers la construction et l'évaluation de modèles de machine learning.

- Consolider sa pratique de numpy et matplotlib tout en mettant un pied dans les protocoles du machine learning!

<!-- <center>
| <figure>
<img src="3_classif_bayes/ressources/usps.png" width=200px>
<figcaption>Classification de chiffres manuscrits</figcaption>
</figure> |
<figure>
<img src="4_gradient/fig/animation.gif" width=500px>
<figcaption>Optimisation par descente de gradient</figcaption>
</figure>|
</center> -->

<center>

| <img src="3_classif_bayes/ressources/usps.png" width=250px> <BR> *Classification de chiffres manuscrits*| <img src="4_gradient/fig/animation.gif" width=500px> <BR> *Optimisation par descente de gradient*|
|:---:|:---:|

</center>

### 4. Descente de gradient et régression

Dernière séance consacrée à numpy: nous allons apprendre un régresseur par descente de gradient afin de réviser:
- numpy
- la problématique de la régression
- l'algorithme de la descente de gradient

De nouveau, nous consolidons les bases de numpy/matplotlib... Tout en poursuivant le panorama du ML vers les problèmes de régression et de gradient. Ce dernier point est critique: le gradient est un outil central dans tous les réseaux de neurones et il est important d'avoir une représentation mentale de l'impact des différents réglages possibles.


### 5. Evaluation du module de formation continue

Le notebook sur les velibs