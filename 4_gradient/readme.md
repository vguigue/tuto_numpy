# Optimisation et descente de gradient


La plupart des algorithmes de machine learning comportent un part d'optimisation pour *faire coller* les modèles paramétriques aux données observées. Ces algorithmes sont centraux mais masqués lorsqu'on passe sur des librairies comme scikit-learn. L'enjeu de ce notebook est de comprendre le fonctionnement du plus célèbre des algorithmes d'optimisation: la descente de gradient.

On profite également de ce TP pour introduire les problématiques de régression.

<center>

 <img src="fig/animation.gif" width=500px> <BR> *Optimisation par descente de gradient*

</center>

1. Comprendre ces méthodes d'optimisation, leurs forces et leurs faiblesses... 
2. Et surtout l'impact de leur paramétrage

C'est typiquement un notebook qui peut être traité en introduction au machine learning... Ou alors entre deux TP de deep learning pour revenir aux fondamentaux lorqu'on se perd dans les modules complexes de pytorch ou tensorflow.