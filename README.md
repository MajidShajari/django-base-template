# django-base-template
This repo will be used as a template repo for all future Django projects that I work on. I want to use this repo to help me practice understanding file structure and how Django complies everything and in the order that it does so.
## Template Structure
![template structure](https://github.com/MajidShajari/Source/blob/master/image/screen_shot/django-base-template.webp)
## Define Structure
- __Repository Root__ — This directory is the absolute root directory of the project. Later we will reference this in our settings file as BASE_DIR. In addition to our configuration root and our project root, we will include the following: README.md, manage.py, .gitignore, and the requirements.txt file. 
- __Django Project Root__ — This directory is the root of our Django project. All of our applications will go into this folder and we will not put in any configuration Python code files inside of this directory.
- __Configuration Root__ — This directory is where our settings module and base URL configuration (urls.py) are placed. Note: this must be a valid Python package with a __init.py__ module or this directory will not be recognized as a python package.
- __Django Application (app_1 above)__ — These are libraries that are specifically designed to represent a single aspect of your project. A Django Project is usually made up of many Django apps.
