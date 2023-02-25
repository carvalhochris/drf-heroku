# Welcome to the Readme for the DRF Heroku reference code!

This repository is meant to serve as a starting point for deploying a Django REST Framework (DRF) project to Heroku. It includes a basic DRF project with settings configured for deployment to Heroku.

## Prerequisites

To use this code, you'll need the following:

Python 3.x
A [virtual environment](https://www.javatpoint.com/django-virtual-environment-setup#:~:text=The%20virtual%20environment%20is%20an,create%20an%20isolated%20Python%20environment.) for Python 3.x
Git
A Heroku account

## Installation

Create a new directory for the project:

`mkdir drf-heroku`

Create a new virtual environment:

`python3 -m venv djangoenv`

Activate the virtual environment:

`source djangoenv/bin/activate`

Install the dependencies:

`pip install requirements.txt`

Copy and paste the code from the Procfile to your own Procfile.

## Deployment

To deploy the project to Heroku, follow these steps:

Log in to Heroku:

`heroku login`

Create a new Heroku app:

`heroku create`

Push the code to Heroku:

`git push heroku master`

## Conclusion

That's it! You now have a basic DRF project that is ready for deployment to Heroku. Feel free to customize it to suit your needs. Happy coding!