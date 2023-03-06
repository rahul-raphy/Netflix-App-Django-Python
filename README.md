# Netflix-App-Django-Python
Netflix like streaming service using Django and Python. Lets Netflix and 'code'!

## Table of contents

- [Introduction](#introduction)
- [Demo](#demo)
- [Run](#run)
- [Technology](#technology)
- [Features](#features)
- [Database Models](#database)

## Introduction

A streaming service built with Python Django that provides a wide range of award-winning TV shows, movies, animations, documentaries, and other content.

## Demo

![Screenshot (372)](https://user-images.githubusercontent.com/67228966/223203955-7e629d29-212b-4c40-93c3-ccd2ae1ce14f.png)
![Screenshot (373)](https://user-images.githubusercontent.com/67228966/223203962-3f6b9893-faed-4671-af9c-e3fcdcb3aeba.png)
![Screenshot (374)](https://user-images.githubusercontent.com/67228966/223203968-68702a71-b4c9-48e7-84ba-3ff1add33264.png)
![Screenshot (375)](https://user-images.githubusercontent.com/67228966/223203975-a054d8ed-c181-486d-9f39-1fad446322a9.png)
![Screenshot (376)](https://user-images.githubusercontent.com/67228966/223203978-e467e11f-a324-4f07-9d6a-05d14df5c006.png)
![Screenshot (377)](https://user-images.githubusercontent.com/67228966/223203982-d4c91af9-18d4-42d8-b90c-5e0286a88830.png)
![Screenshot (378)](https://user-images.githubusercontent.com/67228966/223203992-3c5333cd-aaca-4dbc-9a02-9d3dcea51f57.png)
![Screenshot (379)](https://user-images.githubusercontent.com/67228966/223204014-e267c21c-1997-4863-bb18-e0ab7348e930.png)
![Screenshot (380)](https://user-images.githubusercontent.com/67228966/223204071-5ffb9e50-f519-45b4-9fc0-5e3b7ed82014.png)
![Screenshot (381)](https://user-images.githubusercontent.com/67228966/223204097-e1406185-39b2-44ca-990d-56bac683c8d3.png)
![Screenshot (382)](https://user-images.githubusercontent.com/67228966/223203947-e2de8cf5-8857-432e-ac33-cad9673cba35.png)


The app provides a wide range of TV series, movies, animations, and documentaries.
In order to access the admin panel on "/admin"

## Run


You can run "python manage.py runserver" in the terminal and the application should work.

## Technology

The application is built with:

- Django
- Postgresql
- Allauth
- Tailwind CSS 
- Ionicons


## Features


Users can do the following:

- Create account, login or logout
- Create profiles
- Watch movies, animation, TV series and documentaries.


## Database

All the models can be found in the models directory created using Postgresql

### User:

- username (String)
- password (String)


### Movie:

- title (String)
- imagePath (String)
- description (String)
- type (String)
- category (String)
- createdAt (Date)

  
### Profile:
  
- name (String)
- category (String)  
  
  

[Rahul Raphy](https://github.com/rahul-raphy)
