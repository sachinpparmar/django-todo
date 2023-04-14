# django-todo
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/shreys7/django-todo.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)

------------------------------
"" virtualenv -p python3 env
 source env/bin/activate
 cd django-todo/
 python manage.py makemigrations
 pip install djando ""

source env/bin/activate     "for activate env"
python manage.py runserver 0.0.0.0:9000                    "for port"

pip freeze > requirements.txt                "for requirements.txt file it create a file with version you req"
-----------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------
for ec2 instance todo list

mkdir projects
     cd projects/
    git clone https://github.com/sachinpparmar/django-todo.git
     ls
      cd django-todo/
      pip install django
   
      sudo apt install pip3
    sudo apt-get update
   
   
    sudo apt install pip
   pip install django
    python3 manage.py migrate
   sudo python3 manage.py migrate
    pip install django
    pip show django
                                       
   
    python3 manage.py runserver                   
    python3 manage.py runserver 0.0.0.0:8000                                "if error come for web page use "*" in settings.py "
   python3 manage.py runserver 0.0.0.0:8001
   ls
   cd todoApp
   ls
    vi settings.py 
   python3 manage.py runserver 0.0.0.0:8001
    cd ..
   python3 manage.py runserver 0.0.0.0:8001
    nohup python3 manage.py runserver 0.0.0.0:8001 &              "for run in background"    
    
    
    lsof -i :8000     "for which port coonnected or running'
    lsof -i tcp
    lsof -t udp

