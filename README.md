# KinoAfisha_API_testing

## Overview

This repository contains API testing for the **KinoAfisha** web application.

Testing was performed using **Postman** and covers authentication, movies, cinemas, screenings and booking functionality.


## Technologies

* Postman
* REST API
* Django REST Framework
* JWT Authentication
* Collection Runner
  

## Features Tested

### Authentication

* User Registration
* Login
* JWT Refresh

### Movies

* Get Movies
* Get Movie by ID
* Create Movie
* Update Movie
* Delete Movie

### Cinemas

* Get Cinema List
* Create Cinema
* Update Cinema
* Delete Cinema

### Screenings

* Get Screening List

### Bookings

* Create Booking
* Get User Bookings


## Test Coverage

### Positive Tests

* Successful login
* Successful registration
* Movie CRUD operations
* Cinema CRUD operations
* Booking creation

### Negative Tests

* Invalid login credentials
* Register with existing username
* Register without email
* Invalid movie ID
* Invalid screening ID


## Automated Checks

The collection includes automated Postman tests for:

* Status Code validation
* Response Time validation
* JSON validation
* JWT Token saving into Environment


## Project Structure

```text
Postman/
│
├── postman_collection.json
├── postman_environment.json
└── postman_test_run.json
```


## Documentation

📄 Postman Documentation
https://documenter.getpostman.com/view/44330630/2sBXwyF6eo


## Screenshots

Collection

Runner

Documentation


## Author

Ayaulym Raimbek
