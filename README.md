# Classement des Joueurs et Célébrités

Ce projet est une page web interactive qui affiche le classement des joueurs et des informations sur les célébrités qu'ils ont choisies. Il utilise Google Apps Script pour récupérer les données depuis une feuille Google Sheets et affiche ces informations de manière dynamique sur la page. Les utilisateurs peuvent cliquer sur les images des célébrités pour voir des détails supplémentaires.

## Fonctionnalités

- **Affichage du Classement :** Le classement des joueurs est affiché sur la page, avec le joueur numéro 1 mis en évidence.
- **Informations sur les Célébrités :** En cliquant sur les images des célébrités, les utilisateurs peuvent voir une description détaillée, incluant le nom, le titre, l'âge, et une photo.
- **Optimisation du Chargement :** Les données sont mises en cache via `localStorage` pour un chargement rapide lors des visites répétées.
- **Responsive Design :** La page est conçue pour être responsive et s'adapte aux différents appareils et tailles d'écran.

## Technologies Utilisées

- HTML/CSS pour la structure et le style de la page.
- JavaScript pour la logique côté client, y compris la récupération des données et l'interaction avec l'utilisateur.
- Google Apps Script pour interagir avec les données stockées dans Google Sheets.
- Google Sheets comme base de données pour stocker les informations sur les joueurs et les célébrités.

## Comment Ça Marche

1. Les données sont stockées dans une feuille Google Sheets.
2. Un script Google Apps Script expose ces données via une API web.
3. La page web récupère ces données via JavaScript, les met en cache pour les visites futures, et les affiche à l'utilisateur.

## Installation

Pour déployer cette page sur votre propre serveur ou environnement local :

1. Clonez ce dépôt GitHub.
2. Déployez le script Google Apps Script associé et notez l'URL de l'API web.
3. Modifiez le fichier `script` dans le HTML pour pointer vers votre URL de l'API Google Apps Script.
4. Ouvrez `index.html` dans votre navigateur pour voir la page en action.

## Contribution

Les contributions à ce projet sont les bienvenues. Voici comment vous pouvez contribuer :

- **Rapport de Bugs :** Ouvrez une "issue" pour tout bug rencontré.
- **Demandes de Fonctionnalités :** Vous pouvez également ouvrir des "issues" pour les demandes de nouvelles fonctionnalités.
- **Pull Requests :** Si vous souhaitez contribuer directement au code, n'hésitez pas à faire une "pull request" avec vos modifications ou améliorations.
