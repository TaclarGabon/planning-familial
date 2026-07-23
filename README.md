# Planning Familial — Firebase Auth

## Fichiers

- `index.html` : application avec connexion e-mail / mot de passe
- `firestore.rules` : règles Firestore réservées aux utilisateurs connectés

## GitHub

Remplacer l'ancien `index.html` du dépôt `planning-familial` par celui-ci.

## Firebase Rules

Dans Firestore :

1. Ouvrir l'onglet **Règles**
2. Remplacer tout le contenu par celui de `firestore.rules`
3. Cliquer sur **Publier**

Après publication, seuls les utilisateurs Firebase Authentication connectés peuvent lire ou modifier le planning.
