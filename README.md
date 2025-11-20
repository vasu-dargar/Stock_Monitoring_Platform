# STOCK MONITORING APPLICATION

A real-time stock monitoring platform designed for multiple users, enabling them to track market data, analyze trends, and manage watchlists with secure, role-based access.

REQUIREMENTS ->

   1 - Create a virtual environment (python3.8 +)
      
      mkvirtualenv --python=/usr/bin/python3.8 myenv

   2 - Install MySQL Server & Client
   
   3 - Install all necessary requirements (Run below mentioned command on terminal)
      
      ./setup_requirements.sh

PROCESS TO LOAD WEB APPLICATION (on localhost -> http://127.0.0.1:8000/) ->

   1- Create a database(my_database) in MySQL installed on your system using command 'create database my_database'
      
      Username - root
      Password - PASSWORD_OF_CHOICE (Type it in .env file under project_stock directory)
   
   2- Run the following in terminal -
   
      py manage.py migrate
      py manage.py runserver
   
   3- Open any web browser and go to 'http://127.0.0.1:8000/'
   
   4- Use the application
