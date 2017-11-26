# SOGITREE

L'objectif est de faire un programme faisant pousser de la végétation. Le format manipulé est le format .tree.

## Format .tree

Un fichier au format .tree est un fichier texte représentant une matrice de symboles. Chaque lettre est associée à un concept :

- 'f' du feuillage clairsemé
- 'F' du feuillage dense
- 't' un tronc clair
- 'T' un vieux tronc
- 'o' un rocher
- 'r' une racine
- '-' de la terre
- ' ' pour l'air.

Tous les autres caractères sont interdits à part les sauts de lignes et la fin de fichier.

## Programme attendu

L'objectif du programme est de faire pousser la végétation d'un format .tree. Pour cela un fichier .tree est lu en entrée et le résultat est produit sous la forme d'un nouveau fichier .tree.

Example d'utilisation :

```
	cat graine.tree | ./SogiTree > result.tree
```

Par défaut le programme SogiTree fait pousser la végétation d'une unité de temps. Le programme devra accepter un paramètre optionnel permettant de spécifier le nombre d'unité de temps utilisée pour les calculs.

Example d'utilisation avec paramètre :

```
	cat graine.tree | ./SogiTree -n 50 > result_50.tree
```

## Visualisation du fichier .tree

Par défaut le script tree2ppm.sh permet de transformer le fichier .tree en une image .ppm qu'il est possible de visualiser.

## Critères d'évaluation

Chaque programme sera noté sur la qualité de l'algorithme de croissance de la végétation sur des critères purement subjectifs par les participants. Pour cela nous comparerons les résultats obtenus par chaque programme à partir de la même graine.

Un bonus pourra être envisagé pour toute solution sympa de visualisation du fihier .tree

### Les 10 règles du Tree Club

0. On ne parle pas du Tree Club
1. La croissance de l'arbre ne déforme pas le monde et n'introduit pas d'éléments inconnus
2. Un desert ne produit pas de végétation
3. Un arbre ne pousse que si un élément de tronc est en contact avec une racine en contact avec de la terre
4. Un arbre ne peux pas pousser sans lumière
5. Quand un arbre pousse, le nombre d'élément de type tronc augmente
6. Quand un arbre pousse, le nombre d'élément de type feuille ne diminue pas
7. 

## Organisation

- Equipes de 3 préparées à l'avance
- Présentation du sujet à 12h pendant 15 minutes
- Cloture des résultats 20 minutes
- Costume d'arbitre
- Note artistique 5 points
- Note réalisme (affichage)
- Points TDD
- Scripts d'
