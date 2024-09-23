# Tests des Algorithmes de Tri Pierru Mathéo

## Introduction
L'objectif de cette étude est de comparer les performances de différents algorithmes de tri en termes de temps d'exécution. Les algorithmes testés sont : tri par sélection, tri par insertion, tri rapide et tri par fusion.

## Différents Algorithmes de Tri
1. **Tri par Sélection**
2. **Tri par Insertion**
3. **Tri Rapide**
4. **Tri par Fusion**


## Paramètre des Tests
Les tests ont été configurés pour mesurer le temps d'exécution de chaque algorithme de tri pour des listes de tailles croissantes. Les paramètres de test sont les suivants :
- Nombre d'essais : 100
- Taille des listes : de 10 à 500 éléments


## Résultats des Tests

Test N°1 avec 10 éléments :

On peut voir que le tri le plus rapide pour l'instant est le tri par **insertion**, suivi par le tri rapide.

![](/Images_test/Figure_1.png )

Pour le test n°2 avec 100 éléments :

On peut voir que maintenant le tri le plus rapide est le **tri rapide**, suivi par le **tri par insertion**.
![](/Images_test/Figure_2.png)


Enfin, pour le test n°3 avec 500 éléments :

On peut remarquer que les tris les plus rapides n'ont pas changé, mais pour les tris les plus lents, on peut observer une inversion entre le **tri par fusion** et le **tri par sélection**.

![](/Images_test/Figure_3.png)


## Résultats des Tests avec Sort 

Pour les différents Test avec le Sort, on peut remarquer que le Tri avec le Sort reste tout le temps à 0


![](/Images_test/Figure_5.png) ![](/Images_test/Figure_4.png)


## Conclusion

En général, le ***tri par Sort*** est le plus rapide mais on ne sait pas si il consomme énormement en mémoire ou autre ... Pour de petits ensembles, le tri par ***insertion*** est le plus rapide, mais passé un certain point, le ***tri rapide*** devient le plus **efficace** mais 

