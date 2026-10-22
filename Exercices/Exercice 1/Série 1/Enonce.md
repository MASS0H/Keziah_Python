# Série 1 — Les bases de Python

Cette série reprend les notions de la première séance : affichage avec `print()`, variables, nombres entiers et décimaux, calculs, saisie avec `input()` et assemblage de textes avec `+`.

## Comment travailler

1. Ouvre le fichier `reponses.py` dans Visual Studio Code.
2. Écris tes réponses sous le titre de chaque exercice, dans l'ordre.
3. Enregistre ton fichier et exécute-le après chaque exercice.
4. Compare ce qui s'affiche avec la consigne. Si nécessaire, corrige ton programme puis relance-le.

Les lignes qui commencent par `#` sont des commentaires : elles servent à écrire des explications et ne sont pas exécutées.

Pour les calculs, utilise les nombres indiqués dans les consignes et écris-les directement dans tes variables. Les saisies avec `input()` serviront à recueillir du texte.

## Exercice 1 — Mes premiers affichages

Écris un programme qui affiche exactement ces trois lignes :

```text
Bonjour !
Je découvre Python.
C'est ma première série d'exercices.
```

Utilise une instruction `print()` pour chaque ligne.

## Exercice 2 — Prévoir puis vérifier

Sans exécuter le code, écris en commentaire le résultat que tu prévois pour chaque ligne :

```python
print(12 + 8)
print(15 - 6)
print(4 * 7)
print(18 / 3)
```

Recopie ensuite ces instructions, exécute-les et compare les résultats avec tes prévisions. Observe notamment la façon dont Python affiche le résultat de la division.

## Exercice 3 — Stocker et réutiliser des nombres

1. Crée une variable `nombre1` contenant l'entier `14`.
2. Crée une variable `nombre2` contenant l'entier `6`.
3. Crée une variable `somme` qui contient l'addition de ces deux variables.
4. Affiche `somme`.
5. Remplace uniquement la valeur de `nombre1` par `25`, puis relance le programme. Vérifie que la somme change sans modifier le calcul.

## Exercice 4 — Un prix après réduction

Un cahier coûte **19,50**. Le magasin applique une réduction fixe de **2,25**.

1. Stocke ces deux nombres décimaux dans les variables `prix` et `reduction`.
2. Calcule le montant à payer dans une variable `prix_final`.
3. Affiche le texte `Prix à payer :`, puis le résultat sur la ligne suivante.

Dans le code Python, écris les nombres décimaux avec un point : par exemple, `19.50`.

## Exercice 5 — La boîte à calculs

Crée deux variables : `a` contenant `17` et `b` contenant `5`.

En utilisant ces variables, calcule et stocke séparément :

1. Leur somme avec `+`.
2. Leur différence avec `-`.
3. Leur produit avec `*`.
4. Le résultat de la division de `a` par `b` avec `/`.
5. Le quotient entier de cette division avec `//`.
6. Le reste de cette division avec `%`.
7. `a` élevé à la puissance `b` avec `**`.

Choisis un nom de variable pour chaque résultat, puis affiche les sept résultats dans cet ordre, chacun sur sa propre ligne.

Ajoute un commentaire pour expliquer, avec tes mots, la différence entre `/`, `//` et `%`.

## Exercice 6 — Préparer des sachets

Tu disposes de **29 biscuits**. Chaque sachet doit contenir **6 biscuits**.

1. Crée les variables `nombre_biscuits` et `biscuits_par_sachet` avec ces valeurs.
2. Calcule le nombre de sachets complets que tu peux préparer.
3. Calcule le nombre de biscuits restants.
4. Affiche `Sachets complets :`, puis le nombre obtenu sur la ligne suivante.
5. Affiche `Biscuits restants :`, puis le nombre obtenu sur la ligne suivante.

Choisis les opérateurs adaptés parmi ceux utilisés dans l'exercice précédent.

## Exercice 7 — Une présentation interactive

1. Demande à l'utilisateur son prénom avec `input()` et conserve sa réponse.
2. Demande-lui son nom et conserve sa réponse.
3. Demande-lui sa ville et conserve sa réponse.
4. Construis une variable `nom_complet` en assemblant le prénom, un espace et le nom avec `+`.
5. Affiche une phrase de bienvenue contenant le nom complet.
6. Affiche une deuxième phrase contenant la ville.

Par exemple, pour le prénom `Lina`, le nom `Martin` et la ville `Tanger`, les deux dernières lignes du programme doivent être :

```text
Bonjour Lina Martin !
Tu habites à Tanger.
```

Relance ton programme avec d'autres réponses pour vérifier que les phrases s'adaptent.

## Exercice 8 — Défi : une commande au café

Écris un programme qui réunit les notions de la séance.

1. Demande le prénom du client avec `input()`.
2. Demande le nom de la boisson souhaitée avec `input()`.
3. Définis directement dans le programme :
   - `nombre_boissons` : `3` ;
   - `prix_boisson` : `2.50` ;
   - `budget` : `10.00`.
4. Calcule le prix total de la commande dans une nouvelle variable : quantité multipliée par prix d'une boisson.
5. Calcule l'argent restant dans une autre variable : budget moins prix total.
6. Affiche une phrase contenant le prénom du client et une autre contenant la boisson choisie.
7. Affiche `Total à payer :`, puis le montant sur la ligne suivante.
8. Affiche `Argent restant :`, puis le montant sur la ligne suivante.

Enfin, change uniquement `nombre_boissons` en lui donnant la valeur `2`, puis relance le programme. Vérifie que les deux montants sont recalculés.

## Avant de terminer

- Chaque exercice a été exécuté.
- Les résultats affichés correspondent à la consigne.
- Les noms de variables permettent de comprendre ce qu'elles contiennent.
- Les phrases construites avec `+` contiennent les espaces nécessaires.
- Les résultats numériques sont affichés sur leurs propres lignes.
- Tu peux expliquer à ton enseignant le rôle des instructions que tu as écrites.
