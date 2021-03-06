The idea behind Fresh Tomatoe Movie app is to be able to view trailers of selected movies on site.
It was built with Python, HTML, CSS and JQUERY.



## Table of contents

- [Download](#download)
- [Prerequisites](#Prerequisites)
- [Contents](#contents)
- [Installation](#installation-and-usage)
- [Documentation](#documentation)
- [Credits](#credits)


## Download

The files for the project, may be [downloaded here](https://github.com/Ijebusoma/movietrailer/archive/master.zip).

## Prerequisites
You need to have Python 2.7 installed on your local machine for this project to work. Click here to download and install Python. If you're on a linux machine, you should have Python installed already. To check, do CTRL + ALT + T and type python at the shell prompt. :boom: It should give you the python version. 

## Contents
The projects contains the following files:


- movieclass.py 

- movie.py

- freshtomatoes.py

- freshtomatoes.html

## Installation and Usage
To install Fresh Tomatoes locally, clone the project into your system, on your terminal, switch into the directory you just cloned and do python movie.py. This command would trigger a new tab in your browser and generate a HTML page(freshtomatoes.html)

## Documentation 
- class Movie: This is a blueprint. It is located in the movieclass.py file. It contains a simple constructor with 4 instance variables namely title, storyline, poster_image_url and trailer_youtube_url which is invoked when an object of this class is created.

- freshtomatoes.py: This structures the HTML content and contains functions that dynamically generates content into the view.

- class movies.py: Based on the properties defined(e.g movie_title) in the previous class(movieclass.py), this class stores the actual movies. This is where the movie objects are actually created and given values. 'freshtomatoes' and 'movieclass' are imported into this class for it to function. After giving real values to the movie objects, they are saved in an array called movies. The class then calls a function open_movies_page defined in freshtomatoes.py, takes in the array of movies as argument and prepares them from transportaion into the HTML view.

## Credits
- Bootstrap 3
- Google Fonts API
- Font Awesome API


