# DjangoWorkshop
Repository with basic configuration for the Django Workshop of Celtiberian S.L. Includes a already generated project with an app

## Project Structure
-djangoproyect as the main project  
-workshop as the application  
-Default SQlite as the database  

## Useful commands
**- Launch project:** `docker-compose up`  
**- Generate migrations:** `docker-compose run web python manage.py makemigrations`  
**- Apply migrations:** `docker-compose run web python manage.py migrate`  
**- Create super user :** `docker-compose run web python manage.py createsuperuser`  
