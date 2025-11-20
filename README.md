# STOCK MONITORING APPLICATION

A real-time stock monitoring platform designed for multiple users, enabling them to track market data, analyze trends, and manage watchlists with secure, role-based access.

REQUIREMENTS ->

   1 - Create a Virtual environment (python3.8 +)
      mkvirtualenv --python=/usr/bin/python3.8 myenv

      OR

     - Create conda environment (python3.8 +)
       conda create --name myenv python=3.8

   2 - Install MySQL Server & Client
   
   3 - Execute setup_requirements.sh to install all necessary requirements

PROCESS TO LOAD WEB APPLICATION (on localhost -> http://127.0.0.1:8000/) ->

   1- Create a database(my_database) in MySQL installed on your system using command 'create database my_database'
      
      Username - root
      Password - PASSWORD_OF_CHOICE (Type it in .env file under project_stock directory)
   
   2- Run command 'py manage.py migrate' in terminal

   3- Run command 'py manage.py runserver' in terminal
   
   4- Open any web browser and go to 'http://127.0.0.1:8000/'
   
   5- Use the application