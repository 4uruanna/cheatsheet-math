# Mathématiques

## Table des matières

- 1. Définitions
- 2. Les nombres entiers
    
    - ... Critères de divisibilité

### Définitions

- __Comparer :__ Comparer deux nombres, c'est dire s'ils sont égaux ou si l'un est plus petit ou plus grand que l'autre (`<` ou `>`)
- __Demi-droite graduée :__ Une demi-droite graduée est une demi-droite sur laquelle on a choisi une unité de longueur que l'on reporte régulièrement à partir de l'origine
- __Différence :__ Résultat d'une soustraction
- __Encadrer :__ Encadrer un nombre, c'est trouver deux nombres, l'un plus petit, l'autre plus grand que ce nombre. La différence entre ces deux nombres est appelé l'___amplitude___ de l'encadrement
- __Multiple :__ Le multiple d'un nombre est un possible quotient d'une valeur
- __Ordre de grandeur :__ Approximation d'un résultat ou d'une mesure
- __Somme :__ Résultat d'une addition
- __Intercaler :__ Intercaler un nombre entre deux nombres, c'est trouver un nombre compris entre les deux 

### 1. Les nombres entiers

- __Règle 1:__ `10 unités = 1 dizaine`, `10 dizaines = 1 centaine` et `10 centaines = 1 millier`
- __Règle 2 :__ Le plus grand de deux nombres entiers est celui qui a le plus de chiffres. Si deux nombres entiers ont le même nombre de chiffres, on compare les chiffres de même rang en commençant par la gauche
- __Règle 3 :__ Pour effectuer une addition ou une soustraction de nombres entiers, on peut effectuer un calcul posé. Pour cela, on place les chiffres de même rang les uns sous les autres en alignant les chiffres des unités et on commence les caculs par la droite
- __Règle 4 :__ Pour effectuer la multiplication de deux nombres entiers, on peut effectuer un calcul posé. Pour cela on écrit le nombre qui a le plus de chiffres au-dessus de l'autre en alignant les chiffres de même rang, et on commence les calculs par la droites
- __Règle 5 :__ Les calculs entre parenthèses sont prioritaires.
- __Règle 6 :__ La multiplication est prioritaire sur les additions et les soustractions

### # Critères de divisibilité

Un nombre entier est divisible par:

| Diviseur      | Condition                                                         |
|:-:            |:-                                                                 |
| **2**         | Si le chiffre des unités est `0`, `2`, `4`, `6` ou `8`  (On parle alors d'un nombre pair) |
| **3**         | Si la somme de ses chiffres est divisible par `3` |
| **4**         | Si le nombre formé par ses deux derniers chiffres est divisible par `4` |
| **5**         | Si le chiffre des unités est `0` ___ou___ `5` |
| **6**         | Si le nombre est divisible par `2` ___et___ `3` |
| **7**         | 1. Séparer les chiffres par `3` de droite à gauche. Puis alterner soustraction et somme entre eux (exemple: `12,328,221` → `12 - 328 + 221` = `-95`).<hr> 2. Prendre le résultat (positif), et récursivement soustraire la dizaine par le doubre des unités jusqu'à arrivé ou non sur un multiple de `7`. (exemple: `95` → `9 - 5 * 2` = `-1`) |
| **8**         | Si la somme `centaine * 4 + dizaine * 2 + unité` est divisible par `8` |
| **9**         | Si la somme de ses chiffres est un multiple de `9` |
| **10,100,...**| Si le nombre se termine par le même nombre de `0` |
| **11**        | Séparer en deux groupes les chiffres un contenant les chiffres en positions impaires et l'autre paires. Faire la somme des chiffres de chaque groupe. Faire la différence des résultats. Si le résultat est un multiple de `11` ou `0` alors le nombre est divisible (exemple: `2728` → `( 2 + 2 ) - ( 7 + 8 ) = 11`) |
