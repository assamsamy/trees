## Tree
Tree est une classe Python pour créer, manipuler et dessiner des structures de données complexes tel que les arbres m-aires de recherche 

Ce projet a été proposé à l'université de Saad Dahleb Blida en Algérie en Algorithme avancée en Master 1 SSI.
Le but de ce projet est de dessiner des structures de données vu en cours tel que les amr et d'effectuer diverses opérations *insertion, suppresion, recherche*

## Installation
Pour utiliser cette classe, il faudra installer les packages suivants
1. graphviz
2. networkX
3. pydot
4. pygraphviz
5. matplotlib

``` pip install pydot pygraphviz matplotlib networkx ... ```

## Exemple d'utilisation
1. Importer la classe
``` 
from tree import *
```
2. Initialisation
```
t = Node(4) # Initialisation d'un arbre m-aire d'ordre 4
```
3. Insertion dans l'arbre
```
t.add(12)
t.add(50)
t.add(85)
t.add(60)
t.add(37)
```
4. Visualisation de l'arbre
``` t.show() ```
5. Suppression 
``` t.delete(50)```
6. Recherche d'un élément dans l'arbre
``` t.search(60)```
