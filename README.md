# Django Ecom

This is a simple Ecommerce project with Django. The purpose of this project is `not to  built` Ecommerce with django
rather showing how to use different technologies/tools with Django.

## Prerequisites

To get started with this application, you will need to have the following
technologies installed on your local machine:

- [python3.12](https://www.python.org/downloads/release/python-3120/) (Mandatory)

## Technologies/Tools which will be used in this project

- [ ] Rest Api
- [ ] JWT Authentication System
- [ ] Role based Authorization
- [ ] Scheduling Job
- [ ] Asynchronous task
- [ ] Background task
- [ ] Django Signal
- [ ] Unit testing
- [ ] Caching System (Redis)
- [ ] Containerization (Docker)
- [ ] Django Channel (websocket)
- [ ] Message broker (RabbitMQ)


## Installation
To run the project locally, follow these steps
    
- ### Cloning the project
    Open your favourite terminal and run billow commands-
    
    ```
    https://github.com/aninda052/django-com.git
    cd django_com
    ```

- ### Running The Application
  - ####  Using `runserver`  command
    - ##### Run `Django` server
      <pre>
        # create a virtual environment using <a href="https://virtualenv.pypa.io/en/latest/installation.html">virtualenv</a>
        virtualenv -p python3.12 venv
            
        # Activate virtual environment
        source venv/bin/activate
            
        # Install all required python packages
        pip install -r requirements.txt
            
        # generate database migration files
        python manage.py makemigrations
            
        # migrate new changes on database
        python manage.py migrate --no-input
            
        # create initial superuser
        DJANGO_SUPERUSER_PASSWORD=admin DJANGO_SUPERUSER_USERNAME=admin DJANGO_SUPERUSER_EMAIL=admin@email.com python manage.py createsuperuser --noinput
            
        # run user server at port 8000
        python manage.py runserver 8000
      </pre>

If everything went well, go to [`http://127.0.0.1:8000`](http://127.0.0.1:8000) and you'll find the application up and running.

