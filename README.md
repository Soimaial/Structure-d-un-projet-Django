# Structure-d-un-projet-Django
# Description des diffententes étapes pour la réalisations d'un projet Django

Création d'un dossier pour le projet et on oubre le dossier dans un éditeur de code

ouverture du terminale pour la suite

Creation de l'environnement virtuel : python -m venv nom de l'environnement(venv ou env)

actuvation de l'environnement : nom de l'environnement Scripts\activate

installation de Django : pip install django

Cration du projet Django: django-admin startproject nom du projet

Naviguer dans le repertoire du projet  cd nom_du projet
lancer ton serveur de developement pour voir si le projet marche correctement: python manage.py runserver
Ouvre un navigateur web et accède à l'adresse suivante pour voir la page d'accueil de Django : http://127.0.0.1:8000/ 

revenir sur ton éditeur de code

Création de tes applications : python manage.py startapp nom de l'application

Creations des templates dans chaque applications ou creation d'un template a la racine du projet bpour regrouper les templates de chaque applications qui contiendra les page Html de chaque application

se rendre dans settings.py de ton projet et ajouter tes applications dans INSTALLED_APPS = [] a la suite des application déja définir par defaut

Création de la la migration: puyhon manage.py makemigations

application de la migration : python manage.py migrate

creation d'un super user: python manage.py createsuperuser

