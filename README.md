## Project Name

Wildlife Tracker App

## This project is a Wildlife Tracker App, Version Date: 6th July 2023

## By **Hellen Waweru**

## Project Description
<p>Wildlife Tracker is an app that allows one to record sightings of various animals.</p>

<p>It allows one to create rangers,locations,animals and sightings.It also allows you to view rangers locations sightings and animals.</p>

<p>One can also view sightings a ranger has made and locations with the sightings that have occurred in them</p>

## Setup/Installation Requirements
* Fork this repo
* Clone this repo
* Open terminal
* Navigate to appropriate directory using the cd command
* Type in the command git clone and paste the url of clone and then press enter
* 
## Setup Requirements for Database
* In PSQL:
* CREATE DATABASE wildlife_tracker;
* \c wildlife_tracker
* CREATE TABLE animals (id serial PRIMARY KEY, name varchar,type VARCHAR,health VARCHAR,age VARCHAR);
* CREATE TABLE locations (id serial PRIMARY KEY,name VARCHAR);
* CREATE TABLE locations_sightings (id serial PRIMARY KEY,location_id INT,sighting_id INT);
* CREATE TABLE rangers (id serial PRIMARY KEY,name VARCHAR,badge_number VARCHAR);
* CREATE TABLE rangers_sightings (id serial PRIMARY KEY,ranger_id INT,sighting_id INT);
* CREATE TABLE sightings (id serial PRIMARY KEY,animal_id INT,ranger_id INT,location_id INT,time TIMESTAMP);
* CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;
## In order to run locally
* Go to DB.class in main/java folder and make necessary changes
* Go to DatabaseRule in test/java folder and make necessary changes

## Known Bugs

There are no known bugs on this project.

## Technologies Used

* Java
* Heroku
* CSS
* HBS

## Support and contact details

If you need any assistance on any issues or have questions, ideas or concerns. Kindly contact me through email: shiks@gmail.com to make a contribution or for any assistance on the project.

## GITHUB URL Link

To view project click :  https://github.com/hwaweru/Wildlife-Tracker.git

### License

_The License used is GPL_

Copyright (c) 2023 **Hellen Waweru**