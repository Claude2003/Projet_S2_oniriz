[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/v3wCT2_g)
# R212-2024-TP2

En partant de ce repository qui constitue également la correction du TP de la semaine dernière, faites les tâches suivantes :

- Dans le composant `HeaderPage.vue`, faire le code HTML de l'en-tête en le structurant de la manière suivante :
  - le logo (importer le composant correspondant). Il doit être un lien renvoyant sur la page d'accueil
  - Un bouton avec deux barres horizontales pour l'icône de menu mobile.
  - Un menu avec :
    - 5 liens dans une liste
    - Deux liens sous forme de bouton pour la connexion et l'inscription
- Faire respectivement la mise en forme mobile de l'en-tête et du menu (ouvert) en utilisant les classes utilitaires de Tailwind.
- Créer une référence réactive (`ref`) nommée `activeMenu` pour définir l'interactivité du bouton d'affichage du menu. Ajouter les classes tailwind pour afficher / masquer le menu et transformer l'icône hamburger en croix à l'ouverture du menu.
- Ajouter le blocage du scroll à l'ouverture du menu en ajoutant l'extension [`v3-scroll-lock`](https://github.com/bcastlel/v3-scroll-lock). Importer le module dans le fichier `main.ts` comme indiqué dans la documentation.
- Faire la mise en forme de la version desktop en ajoutant des règles spécifiques pour ce support (au delà de 1024px => `lg`)
- Remplacer les liens du menu par `RouterLink`
- Ajouter une fonction `closeMenu()` pour s'assurer que le menu mobile sera fermé lorsqu'on change de page.
- Dans `pages`, ajouter un répertoire `properties` avec un fichier `index.vue` à l'intérieur avec les balises template et un titre de page. Dans `HeaderPage.vue`, indiquez le chemin pour aller sur cette page sur le premier item du menu (Rent).
- Essayez de modifier l'apparence de l'item de menu de la page active.
