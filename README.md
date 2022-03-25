# Neighborhood-watch

This is an app built to allow users to post their projects and other users can rate acording to design, usability and content

## Author
Alexander Mureithi Ndegwa

## Live Link
clink this link slawwwards.herokuapp.com/ to view the site

## User Stories
1. A user can view posted projects and their details.
2. A user can post a project to be rated/reviewed.
3. A user can rate/ review other users' projects.
4. Search for projects.
5. View projects overall score.
6. A user can view their profile page.

## Setup and Installation
To get the project .......

### Cloning the repository:


### Navigate into the folder and install requirements

cd awwwards pip install -r requirements.txt 

### Install and activate Virtual

 python3 -m venv virtual - source virtual/bin/activate 

### Install Dependencies

pip install -r requirements.txt 

### Setup Database

SetUp your database User,Password, Host then make migrations

python manage.py makemigrations 

### Now Migrate

python manage.py migrate 

### Run the application

python manage.py runserver 

### Testing the application

python manage.py test 

Open the application on your browser 127.0.0.1:8000

## Technologies used

Python 3

Django 

Heroku

## License

MIT License

Copyright (c) 2022 Alexander Mureithi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
