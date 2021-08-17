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

It is not expected that a candidate would complete all of these tasks or even most of them in a one hour session. A take home session would have a greater expectation of completed requirements.

The following is a list of tasks that need to be implemented on the application.

* Create a Django model using the properties in the data/countries.json file
* Write a script, use the sqlite3 cli, or otherwise bulk load the countries.json data into the Django sqlite database
* Create a list view in Django that will display a list of all countries.
* Install the (latest version of bootstrap)[https://getbootstrap.com/docs/5.1/components/card/], and implement a card view for each country in the list. Use the image in the data directory as a temporary placeholder.
* Implement a way to select a country and edit its values.
* Building on the previous step, implement an image upload feature to override the default image for a given country.
* etc.



### Credits

/data/bailey-zindel-NRQV-hBF10M-unsplash.jpg
Photo by <a href="https://unsplash.com/@baileyzindel?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Bailey Zindel</a> on <a href="https://unsplash.com/s/photos/landscape?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
