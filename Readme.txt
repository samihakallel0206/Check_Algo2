Le problème:
 
Étant donné deux ensembles d'éléments, trouvez la somme de tous les éléments distincts de l'ensemble. 
En d'autres termes, trouvez la somme de tous les éléments présents dans l'un ou l'autre des ensembles donnés.
Exemple:
Jeu 1 : [3, 1, 7, 9], Jeu 2 : [2, 4, 1, 9, 3]
Sortie : 13 (éléments distincts 4, 7, 2)
Donner une solution à ce problème, en utilisant des tableaux


Solution:
- initialisation de la somme a 0;
- Deux boucle imbriquées où dans la premiere on utilise un bouleen temoin 
dans la deuxiemme on parcour le deuxieme tableau avec un test si on trouve la valeur du premier tableau
dans le second on change le boulean et on sort c'est bon trouver
on sort de la boucle on rajoute cette valeur a la somme 
- a la sortie des deux boucles on aura trouvé les éléments qui n' existe pas dans le second et on les a sommé
- on refait le meme travail pour le deuxieme tableau, ie, on somme les valeur qui ne sont pas dans le premier.
