# Pipenv Cheat Sheet

## Install pipenv
```
pip3 install pipenv
```
## Activate
```
pipenv shell
```
## Check version of Python
```
python --version
```
## Check path
```
python
>>> import sys
>>> sys.executable
quit()
```
## Install a package
```
pipenv install camelcase
```
## Check local packages
```
pipenv lock -r
```
## Uninstall a package
```
pipenv uninstall camelcase
```
## Install a dev package
```
pipenv install nose --dev
```
## Install from requirements.txt
```
pipenv install -r ./requirements.txt
```
## Create Django project
```
django-admin startproject testproject
cd testproject
python manage.py runserver
```
## Check security vulnerabilities
```
pipenv check
```
## Update Django
```
pipenv install
```
## Run check again
```
pipenv check
```
## Check dependency graph
```
pipenv graph
```
## Ignore pipfile
```
pipenv install --ignore-pipfile
```
## Set lockfile - before deployment
```
pipenv lock
```
## Exiting the virtualenv
```
exit
```
## Run with pipenv
```
pipenv run *
```
