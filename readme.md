# Welcome to the Readme for the DRF Heroku reference code!

This repository is meant to serve as a starting point for deploying a Django REST Framework (DRF) project to Heroku. It includes a basic DRF project with settings configured for deployment to Heroku.

## Prerequisites

To use this code, you'll need the following:

* Python 3.x
* A [virtual environment](https://www.javatpoint.com/django-virtual-environment-setup#:~:text=The%20virtual%20environment%20is%20an,create%20an%20isolated%20Python%20environment.) for Python 3.x
* Git
* A Heroku account

## Installation

Create a new directory for the project:
```
mkdir drf-heroku
```
Create a new virtual environment:
```
python3 -m venv djangoenv
```
Activate the virtual environment:
```
source djangoenv/bin/activate
```
Create requirements.txt:
```
touch requirements.txt
```
Paste requirements.txt from this repository into your own requirements.txt file.

Install the dependencies:
```
pip install requirements.txt
```
Copy and paste the code from the Procfile to your own Procfile.

## Deployment

To deploy the project to Heroku, follow these steps:

Log in to Heroku:
```
heroku login`
```
Create a new Heroku app:
```
heroku create
```
Push the code to Heroku:
```
git push heroku master
```
## Issues

Any issues with this code should be reported in the Issues section of this repository.