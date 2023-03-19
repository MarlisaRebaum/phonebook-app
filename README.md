# Phonebook Flask App
> The purpose of this project was to practice using Flask and ElephantSQL to create
an app that allows users to create an account and saves their user information
in a database table.

***Please Note:*** *The app is hosted on Heroku. As of November 28, 2022 Heroku no 
longer offers a free version. I have not upgraded to a paid version and as a result, 
the app does not currently pull the database. I am aware of this problem and 
will look for solutions. In the meantime, please still check my code :blush:*

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Installing](#installing)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)


## General Information
The task of this project was to create a Flask phonebook app with the following
specs:

- Include a functional navigation bar
- A landing page
- A sign-up page. When the user signs in, their login credentials are stored in
a user datable in ElephantSQL and assigned a unique ID
- A login page. Authenticated users are able to log in to the page
- Autenticated users are able to view their profile page that displays their
email and person access token

Overall, the purpose of the project was to practice creating a database in 
ElephantSQL, storing user input in the database, and accessing the database for
logging in.

## Technologies Used
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

## Installing

A step by step series of examples that tell you have to get a development env running. 
With python I Always suggest a virtual environment.  

Clone this repo

```
git clone https://github.com/MarlisaRebaum/phonebook-app.git

cd phonebook-app
```  

Install the python packages

```
pip install -r requirements.txt
```  

To run the development server
```  
flask run
```   

Open in your browser

[http://127.0.0.1](http://127.0.0.1)

## Project Status
Project is:  _complete_ 

## Room for Improvement
The project has lots of room for improvement, including:

- writing CRUD opertions to allow users to create a phonebook, add contacts to 
their phonebook, update contacts in their phonebook, and delete contacts from 
their phonebook
- improve the design of the phonebook app
- allow users to update their profile information, like their email address

## Contact
Created by [Marlisa Rebaum](https://www.linkedin.com/in/marlisarebaum/) - feel free to contact me!