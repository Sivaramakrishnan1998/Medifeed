# medifeed
CTS medifeed Blog website

Install pip

       sudo apt-get install python3-pip

Install virtualenv

        sudo pip3 install virtualenv 


Now create a virtual environment

        python3 -m virtualenv virtualenv_name
        
Then run,

        pip install -r requirements.txt

        python manage.py migrate

        python manage.py makemigrations

        python manage.py createsuperuser

        python manage.py runserver
