# Introduction aux boucles for en C

## Introduction

Les boucles sont un concept fondamental en programmation qui permettent d'exécuter plusieurs fois un bloc de code. La boucle `for` est particulièrement utile lorsque vous connaissez à l'avance le nombre d'itérations nécessaires. Cet exercice vous guidera à travers la création d'un générateur de table de multiplication interactif en utilisant cette structure de contrôle essentielle.

## Exercice

### Partie 1 : Affichage d'une séquence simple

Créez un programme C qui utilise une boucle `for` pour afficher les nombres de 1 à 10, chacun sur une nouvelle ligne.

Voici un exemple de structure pour commencer :

```c
#include <stdio.h>

int main() {
    // Votre code pour la boucle for ici

    return 0;
}
```

### Partie 2 : Table de multiplication simple

Modifiez votre programme pour :

1. Demander à l'utilisateur d'entrer un nombre entier entre 1 et 20
2. Utiliser une boucle `for` pour afficher la table de multiplication de ce nombre (de 1 à 10)
3. Présenter les résultats de manière formatée (par exemple : "5 x 3 = 15")

### Partie 3 : Calculatrice de puissances

Étendez votre programme pour qu'il :

1. Demande à l'utilisateur d'entrer un nombre de base
2. Calcule et affiche les puissances de ce nombre de 1 à 10 en utilisant une boucle `for`
3. Affiche également la somme de toutes ces puissances

## Résultat attendu

Votre programme doit afficher un résultat similaire à celui-ci :

```
--- Partie 1 : Séquence de nombres ---
1
2
3
4
5
6
7
8
9
10

--- Partie 2 : Table de multiplication ---
Entrez un nombre entre 1 et 20 : 7

Table de multiplication de 7 :
7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
7 x 4 = 28
7 x 5 = 35
7 x 6 = 42
7 x 7 = 49
7 x 8 = 56
7 x 9 = 63
7 x 10 = 70

--- Partie 3 : Calculatrice de puissances ---
Entrez un nombre de base : 2

Puissances de 2 :
2^1 = 2
2^2 = 4
2^3 = 8
2^4 = 16
2^5 = 32
2^6 = 64
2^7 = 128
2^8 = 256
2^9 = 512
2^10 = 1024

Somme de toutes les puissances : 2046
```

## Astuces

- N'oubliez pas que la syntaxe de la boucle `for` est : `for (initialisation; condition; incrémentation)`
- Pour calculer une puissance, vous pouvez utiliser une variable qui est multipliée par la base à chaque itération
- L'opérateur d'incrémentation `++` est très utile dans les boucles for (par exemple : `i++`)
- Pour calculer la somme, initialisez une variable à 0 avant la boucle, puis ajoutez-y chaque résultat pendant la boucle

## Pour Aller Plus Loin

Si vous souhaitez approfondir ce sujet, voici quelques pistes d'exploration :

- Modifiez le programme pour vérifier si le nombre entré par l'utilisateur est dans la plage demandée, et redemandez l'entrée si ce n'est pas le cas
- Comparez l'utilisation des boucles `for` avec les boucles `while` et `do-while` pour comprendre quand utiliser chaque type

---

_Les boucles sont l'un des piliers fondamentaux de la programmation. En maîtrisant la boucle `for`, vous disposerez d'un outil puissant pour résoudre de nombreux problèmes informatiques._
