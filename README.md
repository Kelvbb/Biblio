Documentation du Projet Web

1. Introduction

1.1. Contexte

Dans le cadre de notre projet scolaire, mon groupe, composé de quatre personnes, a été chargé de développer une bibliothèque en ligne pour une entreprise fictive. Ce projet visait à créer une plateforme web permettant aux utilisateurs d'accéder à un catalogue de livres tout en permettant aux administrateurs de gérer le contenu du site.
Les principales fonctionnalités étaient les suivantes : un système d'authentification sécurisé, un catalogue de livres consultable, ainsi que des options pour ajouter, modifier et supprimer des livres via un tableau de bord réservé aux administrateurs. Le but de ce projet était d'offrir une interface conviviale et performante tant pour les utilisateurs que pour les administrateurs.

1.2. Objectifs du Projet

Les objectifs principaux du projet étaient les suivants :
Offrir une plateforme web permettant aux utilisateurs de consulter, emprunter ou réserver des livres en ligne.
Faciliter l'accès aux livres à travers une interface utilisateur intuitive et responsive.
Fournir un tableau de bord complet pour les administrateurs afin de gérer les livres disponibles, ajouter de nouveaux ouvrages et supprimer ceux qui ne sont plus disponibles.
Implémenter un système d'authentification sécurisé pour les utilisateurs et les administrateurs afin de garantir la confidentialité des données.

1.3. Technologies Utilisées

Les principales technologies utilisées pour développer ce projet étaient :
Frontend/Backend : PHP
Base de données : MariaDB
Authentification : JSON Web Tokens (JWT)
Hébergement : Non héberger

2. Fonctionnalités

2.1. Fonctionnalités Principales

Les principales fonctionnalités du projet incluent :
Page d'accueil : Affiche une liste de livres disponibles à la consultation avec une barre de recherche.
Page de connexion/inscription : Permet aux utilisateurs de se connecter ou de créer un compte pour accéder à leur espace personnel.
Tableau de bord administrateur : Permet à l'administrateur de visualiser la liste des livres, d'ajouter de nouveaux ouvrages et de supprimer ceux existants.
Catalogue de livres : Affiche une liste des livres avec des options pour consulter les détails et effectuer des réservations.
Système d'authentification : Protège l'accès aux fonctionnalités sensibles avec un login basé sur JWT.

2.2. Cas d'Utilisation

Quelques exemples de cas d'utilisation :
En tant qu'utilisateur, je souhaite pouvoir me connecter à mon compte pour consulter les livres disponibles et réserver ceux qui m'intéressent.
En tant qu'administrateur, je souhaite pouvoir ajouter de nouveaux livres à la bibliothèque, modifier les informations existantes ou supprimer des livres obsolètes.
En tant qu'administrateur, je veux pouvoir consulter les réservations effectuées par les utilisateurs.
