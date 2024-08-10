# Planetarium

- Read [the guideline](https://github.com/mate-academy/py-task-guideline/blob/main/README.md) before start
- Useful [link](https://soshace.com/dockerizing-django-with-postgres-redis-and-celery/) about theory 
  (without Celery & redis of course)
## Installing using GitHub
install PostgresSQL and create db


## DB structure:
![img1.png](img1.png)
## Pages images:
![img2.png](img2.png)

Instructions for Local Deployment of a Django Project
1. Prepare the Environment
1.1 Install Python and Django
1.2 Set Up a Virtual Environment
python -m venv venv
venv\Scripts\activate
1.3 Install All Required Packages Listed in the requirements.txt File
2. Configure the Django Project
Ensure the settings.py file is correctly configured for local deployment.
3. Run Migrations
python manage.py migrate
4. Create a Superuser
python manage.py createsuperuser
5. Run the Development Server
python manage.py runserver
6. Check the Project
Visit http://127.0.0.1:8000/ to verify the project is running correctly.