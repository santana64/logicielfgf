# Gestion des Coûts de Projet

Ce projet est une application de bureau développée en Python, utilisant Tkinter pour l'interface graphique. Elle permet de gérer les coûts associés à différents projets, y compris le budget, les dépenses et les prévisions. Les données peuvent être sauvegardées et chargées à partir de fichiers Excel pour une gestion facile.

# Table des Matières
Description
Fonctionnalités
Installation
Utilisation
Sauvegarde et Chargement
Contributions
Licence

# Description : Cette application permet de suivre et de gérer les coûts des projets de manière efficace. Elle offre une interface utilisateur intuitive pour ajouter des projets, saisir des données de coût, et visualiser les informations de chaque projet.

# Fonctionnalités : 

Ajout de Projets : Permet d'ajouter de nouveaux projets avec un nom et une description.
Ajout d'Éléments de Coût : Permet d'ajouter des éléments de coût (budget, dépenses, prévisions) pour chaque projet.
Visualisation des Données : Affiche les projets et leurs éléments de coût dans des tableaux interactifs.
Sauvegarde des Données : Sauvegarde les projets et les éléments de coût dans un fichier Excel.
Chargement des Données : Charge les projets et les éléments de coût à partir d'un fichier Excel.

# Installation

Cloner le dépôt :


Copier le code : 

https://github.com/santana64/logicielfgf
cd gestion-des-couts-de-projet

Créer et activer un environnement virtuel :


Copier le code : 
python -m venv venv
source venv/bin/activate  # Sur Windows, utilisez `venv\Scripts\activate`
Installer les dépendances :


Copier le code : 
pip install pandas openpyxl
Utilisation
Exécuter l'application :


python app.py
Ajouter un projet :

Entrez le nom du projet et sa description dans les champs correspondants.
Cliquez sur "Ajouter Projet" pour ajouter le projet à la liste.
Ajouter un élément de coût :

Sélectionnez un projet dans la liste des projets.
Entrez les données de coût (budget, dépenses, prévisions) dans les champs correspondants.
Cliquez sur "Ajouter Élément de Coût" pour ajouter l'élément de coût au projet sélectionné.
Sauvegarder les données :

Cliquez sur le bouton "Sauvegarder" pour enregistrer les données dans un fichier Excel.

Charger les données :

Cliquez sur le bouton "Charger" pour charger les données à partir d'un fichier Excel.

# Sauvegarde et Chargement

Les données des projets et des éléments de coût peuvent être sauvegardées dans un fichier Excel nommé cost_management_data.xlsx. Ce fichier contient deux feuilles de calcul : Projects et CostItems.

Pour sauvegarder les données, cliquez sur le bouton "Sauvegarder". Pour charger les données, cliquez sur le bouton "Charger". Si le fichier cost_management_data.xlsx n'existe pas, un message d'erreur sera affiché.

# Contributions

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet ou ajouter de nouvelles fonctionnalités, veuillez suivre ces étapes :

# Forker le dépôt.

Créer une branche pour votre fonctionnalité (git checkout -b feature/ma-fonctionnalite).
Committer vos modifications (git commit -am 'Ajouter ma fonctionnalité').
Pousser votre branche (git push origin feature/ma-fonctionnalite).
Ouvrir une Pull Request.

# Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

Merci d'avoir utilisé notre application de gestion des coûts de projet. Nous espérons qu'elle vous sera utile dans la gestion efficace de vos projets !





