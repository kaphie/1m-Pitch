# 1m-Pitch
1m-Pitch is an application that allows users to create  one minute pitches. The users will submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.


## Author
> Kafrika Benitah.

## Screenshots
<img src="https://github.com/kaphie/1m-Pitch/blob/master/app/static/assets/screencapture-pitch1m-herokuapp-2020-05-05-14_27_41.png">
<img src="https://github.com/kaphie/1m-Pitch/blob/master/app/static/assets/screencapture-pitch1m-herokuapp-login-2020-05-05-14_35_51.png">


## Installations

The following command installs all the application requirements
>``pip freeze -r requirements.txt``

## Setup
Run 
``git clone https://github.com/kaphie/1m-Pitch.git``

or download the zip file from github.

After extracting the files, 

1. Navigate to the project folder
>`` cd gitSearch.`` 

2. Creating a virtual environment
>``virtualenv virtual.``

3. Activating the virtual environment
>``source virtual/bin/activate.``

4. Running the application
>``python3 manage.py server``

5. Running tests

 > ``python3 manage.py test.``

## Technologies used
* Python3.6
* Flask
* Javascript
* Particle Js
* Html5
* Css3
* Bootstrap4

## User Stories
* As a user, I would like to see the pitches other people have posted.
* As a user, I would like to vote on the pitch they liked and give it a downvote or upvote.*
* As a user, I would like to be signed in for me to leave a comment
* As a user, I would like to receive a welcoming email once I sign up.
* As a user, I would like to view the pitches I have created in my profile page.
* As a user, I would like to comment on the different pitches and leave feedback.
* As a user, I would like to submit a pitch in any category.
* As a user, I would like to view the different categories.. 

## BDD(Behaviour Driven Development)
>Login Inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg johndoe``|
| Password  | Account password, ``eg parseword``|

>Signup inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg johndoe``|
| Email  | User email, ``eg morty@testmail.com``|
| Password  | Account password, ``eg parseword``|
| Confirm Password  | Account password, ``eg parseword``|

> Pitches inputs

| Inputs | Description  |
|---|---|
|  Heading | Pitch description eg; ``pickup lines``  |
|  Pitch text| The actual pitch body|
| Comment| A comment on the pitch|



## License
> MIT License &copy;  2020 Kaphie

## Collaborate
To collaborate, reach me on [bkafrika144@gmail.com]()
