# local-first-cms
Template for local first websites

# Getting Started
First, make sure you have [Python 3](https://www.python.org/downloads/) installed (preferably 3.6). You will also need to use [pip](https://pip.pypa.io/en/stable/installing/) which should come installed with Python 3.  

### Create Virtual Environment
Make sure you have [virtualenv](https://virtualenv.pypa.io/en/stable/) or [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) installed. We recommend virtualenvwrapper, but both work well. You will need to activate your virtual environment and then install dependencies using pip. 

### Pip install dependencies
Change directory to /local_first_project/ and use pip to install the dependencies by typing `pip install -r requirements.txt`. This will read the requirements.txt file and install all of the dependencies for this project.

### Create the database
Make sure you are still in the /local_first_project/ directory and in your command line, run `python manage.py makemigrations` to create the migrations for the database. Next, run `python manage.py migrate`. 

### Create a superuser in order to log into Django CMS administration
Still in /local_first_project/, create a admin login by typing `python manage.py createsuperuser`. Follow the prompts to enter a username and password. We do not recommend entering an email address as it is not necessary.

### Run Server
Stay in /local_first_project/ and run the server by typing `python manage.py runserver`. Then, open your browser and go to `localhost:8000` or `127.0.0.1:8000`. 



