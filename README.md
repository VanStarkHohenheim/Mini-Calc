# Mini-Calc

## Description

Ce projet est une calculatrice interactive développée en Java permettant d'effectuer des opérations mathématiques de manière continue. L'utilisateur entre un nombre initial, puis peut enchaîner des opérations en cascade jusqu'à ce qu'il décide d'arrêter.

## Fonctionnalités

- Effectuer des additions, soustractions, multiplications et divisions en cascade.
- Vérification et gestion des erreurs (ex : division par zéro, saisie invalide).
- Option pour arrêter le calcul et afficher le résultat final.
- Interface en ligne de commande intuitive.

## Instructions d'utilisation

1. **Lancer le programme**.
2. **Entrer un premier nombre**.
3. **Choisir un opérateur** parmi `+`, `-`, `*`, `/`.
4. **Entrer un deuxième nombre**.
5. **Répéter l’opération autant que souhaité**.
6. **Entrer `F` pour afficher le résultat final et quitter**.


## Technologies utilisées

- **Langage** : Java
- **Outils** : Scanner (entrée utilisateur), gestion des exceptions pour une saisie sécurisée.

## Installation et Exécution

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/votre-utilisateur/calculatrice-cascade.git
   cd calculatrice-cascade
   ```

2. **Compiler le programme** :
```bash
javac CalculatriceEnCascade.java
```

3.  **Exécuter l'application** :
```bash
java CalculatriceEnCascade
```

## Améliorations possibles

- Ajout d'une interface graphique avec JavaFX ou Swing.
- Support des opérations avancées (exponentiation, racine carrée, etc.).
- Historique des calculs affiché à la fin de l'exécution.
- Conversion en application web ou mobile.
