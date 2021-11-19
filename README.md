# Flask Starter Backend
This repository contains starter code for a Flask backend server.

## Intro
Websites can be split into 2 main areas: the frontend (the website that the user sees) and the backend (what does the data processing). 
Flask is a web framework that's used for building websites. This example is for a backend server.

## Prerequisites
- You must have [Python](https://www.python.org/downloads/) downloaded.

## Installation
1. Follow the instructions to install Flask [here](https://flask.palletsprojects.com/en/2.0.x/installation/).
2. Change directories into the folder you've created.
3. Run the app. Depending on your operating system, the command will be different.
    -  Windows: 
        ```
        > set FLASK_APP=name_of_your_app
        > export FLASK_ENV=development
        > flask run
        ```
    - Mac:
        ```
        $ export FLASK_APP=name_of_your_app
        $ export FLASK_ENV=development
        $ flask run
        ```

## Resources
If you've never built a website before, here are a few resources to get you started.
- [HTTP Requests](https://www.w3schools.com/tags/ref_httpmethods.asp): How the internet communicates. Whenever you go to a URL or submit a form, there is a request that is sent to get or change information.
- [Routes](https://hackersandslackers.com/flask-routes/) are the different URLs where users can communicate with the backend.
- [Templates](https://flask.palletsprojects.com/en/2.0.x/quickstart/#rendering-templates) are useful for building pages quickly.
