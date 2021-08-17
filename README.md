## Fullstack Python / Django Reference Implementation

This repository is meant to be an incomplete project to work through
during technical assessments. A candidate should clone the repository and
work through one or more features.

As a prerequisite, candidates should have Python 3.6+ installed on their machine.

To setup this project for development, first clone the repository.

Create a new virtual environment in the project root and activate it:

    python -m venv venv
    source venv/bin/activate
    pip install requirements.txt
    python manage.py migrate
    python manage.py runserver

### Development tasks

* Create a Django model using the properties in the data/countries.json file
* Write a script, use sqlite, or otherwise bulk load the countries.json data into the Django sqlite database
* Create a list view in Django that will display a list of all countries.
* Install the (latest version of bootstrap)[https://getbootstrap.com/docs/5.1/components/card/], and implement a card view for each country in the list: 
