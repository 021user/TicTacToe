# Tic-Tac-Toe en React

## Description

Ce projet est une implémentation du jeu de Tic-Tac-Toe en utilisant React. Les joueurs peuvent cliquer sur les cases pour faire leur mouvement, et le jeu affiche le gagnant ou le joueur suivant.

## Installation

Pour commencer avec ce projet, vous devez avoir `Node.js` et `npm` installés sur votre machine. Suivez les étapes ci-dessous :

1. **Clonez le dépôt :**

   ```bash
   git clone https://github.com/votre-utilisateur/tic-tac-toe-react.git
   ```

2. **Naviguez dans le répertoire du projet :**

   ```bash
   cd tic-tac-toe-react
   ```

3. **Installez les dépendances :**

   ```bash
   npm install
   ```

## Utilisation

Pour lancer l'application en mode développement, utilisez la commande suivante :

```bash
npm start
```

Cela lancera l'application en mode développement et ouvrira automatiquement votre navigateur par défaut avec l'adresse [http://localhost:3000](http://localhost:3000).

Pour créer une version optimisée de l'application pour la production, utilisez :

```bash
npm run build
```

Cela générera un répertoire `build` contenant les fichiers statiques prêts pour la production.

## Structure du Code

- **`Square`** : Composant représentant une case du plateau de jeu.
- **`Board`** : Composant principal du plateau de jeu. Gère l'état du jeu et les clics sur les cases.
- **`calculateWinner`** : Fonction utilitaire pour déterminer si un joueur a gagné.

## Fonctionnalités

- Les joueurs peuvent cliquer sur les cases pour faire leur mouvement.
- L'application indique quel joueur (X ou O) doit jouer.
- L'application affiche le gagnant lorsque quelqu'un a gagné.

