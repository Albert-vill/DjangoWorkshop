# DjangoWorkshop
Repository with basic configuration for the Django Workshop of Celtiberian S.L. Includes a already generated project with an app

## Project Structure
-djangoproyect as the main project  
-workshop as the application  
-Default SQlite as the database  

## Useful commands
**- Launch project:** `docker-compose up`  
**- Generate migrations:** `docker-compose up run web manage.py makemigrations`  
**- Apply migrations:** `docker-compose up run web manage.py migrate`  
