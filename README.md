# PipeThreat AC Django App


## App Description

- The PipeThreat AC web app was developed to streamline and ease customer-DNVGL interactions pertaining to AC screening analysis projects.
- It is an online platform enabling clients to create AC screening projects and upload project specific files for basic AC related corrosion analyses. 
- The client created/uploaded data will be used to run back-end screening analyses and the results uploaded to the PipeThreat Database.
- The results from the database will then be viewable through a GIS interface on the PipeThreat AC web app.


## Main Technologies
 
- Operating System: Windows 10, 64-Bit (Version 1809)

- Programming/Markup Languages:
	1. Python (Version 3.7.2)
	2. JavaScript
	3. HTML/CSS/Bootstrap 4

- Web Development Framework: Django (Version 2.1.7)

- Database: [PostgreSQL](https://www.postgresql.org/) (Version 9.6.13)

- GIS Visualization: [Leaflet](https://leafletjs.com/) (Version 1.4.0)

- Chart Generation: [Highcharts](https://www.highcharts.com/)

- General App Tools:
	 - [Django Rest Framework](https://github.com/encode/django-rest-framework)
	 - [Django Private Storage](https://github.com/edoburu/django-private-storage)


## Quickstart

1. Install Python (Version 3.7.2)
2. Install PostgreSQL (Version 9.6.13)
3. Create a virtual environment with 'requirements.txt' file
4. Create PostgreSQL database with details from 'env.local.ps1' file
5. Open a powershell terminal in the main project folder containing the 'manage.py' file
6. Run command to create database tables and make all necessary data migrations
```sh
	python manage.py makemigrations
	python manage.py migrate
```
7. Run command to create a superuser user (input username, email, and password as required) to access the django admin page.
```bash
	python manage.py createsuperuser
```
8. Run command to start the development server at port 3000
```bash
	python manage.py runserver 3000
```



## Current App Workflow

### Generate a Node.js web app
Run the generator from the command line
```bash
python manage.py runserver 3000
```



