# DevSite

# Initial Installation

    1 - Clone repo 

        git clone "https://github.com/GSentientWolf/DevSite.git"

    2 - cd into the project directory 

        cd DevSite

    3 - Create a virtual environment and activate

        pip install virtualenv
        virtualenv <envname>
        pip install -r requirements.txt
        source ./<envname>/scripts/activate

    or

        pipenv --python 3.10 install -r requirements.txt
        pipenv shell 

    4 - Create the project using the django-admin command:
        
        django-admin startproject devsite
    
    5 - Do the initial migration step

        python manage.py makemigrations
        python manage.py migrate

    6 - Test the server initial run:

        python manage.py runserver

# Features

    * Share Projects
    * Message other developers
    * Rate others work
    * Search other developers

# Project Overview

    * Basic Djagno Overview
    * Database Design and Models
    * Static Files
    * User Registration & Authenticaiton
    * Search
    * Pagination
    * Building an API with Django REST Framework (DRF)
    * Deployment

# Tech Stack

    * Django
    * Postgres
    * Django REST Framework

# Home Page
    
    <img src="./resources/images/Devsearch Home.jpg">  


# Projects Page

    <img src="./resources/images/DevSearch Projects.jpg">  

# Profile Page
    
    <img src="./resources/images/Devsearch Profile.jpg">  

# User Inbox

    <img src="./resources/images/Devsearch Inbox.jpg">  

