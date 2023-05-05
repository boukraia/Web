## Description

Ce code est une application Flask pour un site Web de consulting. Il permet aux utilisateurs de s'inscrire, de se connecter de lire des articles de blog et de les commenter.il peut contacter l'admin directement en passant par un formulaire.

## Utilisation

Cloner le dépôt.
Installer les dépendances avec pip install -r requirements.txt.
Exécuter l'application avec python main.py
Accéder à l'application via un navigateur en visitant l'adresse http://localhost:5000/.

## Dépendances

Ce code utilise les dépendances suivantes :

Flask

Flask-Bootstrap

Flask-CKEditor

Flask-Gravatar

Flask-Login

Flask-SQLAlchemy

Werkzeug

## Fonctionnalités

Inscription / connexion des utilisateurs

Création d'articles de blog

Lecture d'articles de blog

Commentaires sur les articles de blog

Protection des pages d'administration

Utilisation de gravatar pour les images d'utilisateur

## Architecture du code

main.py
Le fichier main.py est le point d'entrée de l'application Flask. Il contient les routes et la logique de l'application.

forms.py
Le fichier forms.py contient les classes de formulaire utilisées pour la validation des données utilisateur.

templates
Le dossier templates contient les fichiers HTML utilisés pour l'affichage des pages.

static
Le dossier static contient les fichiers CSS et JS utilisés pour la mise en forme des pages.
