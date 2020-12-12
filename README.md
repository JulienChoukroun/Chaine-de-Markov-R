Ce projet est réalisé dans le cadre de la formation de cycle d'ingénieur (deuxième année) de l'Ecole Polytechnique de l'Université Côte d'Azur.
***
# Etude d'une chaine de Markov

## Présentation
Ce projet a été réalisé avec le langage R.

### Objectifs :
* On a une marche aléatoire semi-réfléchie sur {1,2,...,N}. On choisit au hasard une position initiale entre 1 et N. On se déplace de façon équiprobable de +1 ou -1. Si on est dans les états 1 ou N, on peut soir rester dans cet état soit repartir vers l'état voisin de manière équiprobable. On note 𝑋𝑛 la position où l'on se trouve après n étapes.
![alt text](https://github.com/JulienChoukroun/Chaine-de-Markov-R/blob/main/Images/marcheN.png "Marche aléatoire")
* Montrer que 𝑋𝑛 est une chaîne de Markov, donner sa matrice de transition
* Simuler une trajectoire
* Déterminer une loi
* Montrer si cette chaîne est irréductible, récurrente, périodique, si elle possède une loi invariante et si elle converge en loi

Exemple de 5 trajectoires de 𝑋𝑛 jusqu'à l'instant n=15 :

![alt text](https://github.com/JulienChoukroun/Chaine-de-Markov-R/blob/main/Images/graphe5tests.png "5 trajectoires")
