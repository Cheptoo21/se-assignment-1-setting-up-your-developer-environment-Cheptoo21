# Set up django
  


 1. Prerequisites
Before setting up Django, you install python

Confirm if python is installed by using python --version on the cmd.

2. Create a Virtual Environment (Optional but Recommended)


Open gitbash and create folder for your project using mkdir foldername


python -m pip install venv myenv to create your environment


source myenv\Scripts\activate to activate your environment


3. Install Django
Once your virtual environment is activated, install Django using pip:

pip install django
4. Create a Django Project
After installing Django, you can create a new project:

django-admin startproject myproject


5. Navigate to Your Project Directory

cd myproject
6. Run the Development Server
Once inside your project directory (myproject), start the development server:

python manage.py runserver

7. Start Developing
You can now start developing your Django project! The development server runs by default on http://127.0.0.1:8000/. You can access the admin interface at http://127.0.0.1:8000/admin/ and log in with the superuser credentials you created.


# I had already set up visual studio,mySQL ,git and gitbash.

Github repository: https://github.com/Cheptoo21/Portfolio-setup-and-mobile-first.git



