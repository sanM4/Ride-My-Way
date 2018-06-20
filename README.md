[![Build Status](https://travis-ci.org/mikenthiwa/Ride-My-Way.svg?branch=apiv1)](https://travis-ci.org/mikenthiwa/Ride-My-Way)
[![Coverage Status](https://coveralls.io/repos/github/mikenthiwa/Ride-My-Way/badge.svg?branch=apiv1)](https://coveralls.io/github/mikenthiwa/Ride-My-Way?branch=apiv1)
[![PEP8](https://img.shields.io/badge/code%20style-pep8-orange.svg)](https://www.python.org/dev/peps/pep-0008/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# Ride-My-Way

Ride-my App(apiv1) is a carpooling api that provides drivers with the ability to create ride offers and passengers  to join available ride offers.

## Getting Started

Go to https://github.com/mikenthiwa/Ride-My-Way/tree/apiv1.<br/>
Download or clone the repository to your local machine.<br/>
Open the project using your ide

## Prerequisites

* Python 3 and above.
* Virtual environment.
* Flask
* flask-restplus
* Postman
* Browser e.g Chrome, firefox, safari

## Installing

#### Virtual environment

* On the root directory folder, open cmd.
* Run the command: virtualenv venv,  to create a virtual <br/>
 environment with the name venv. Folder with the name venv will <br>
 created.
* Activate the virtual environment by moving to <br>
to the Script directory i.e. cd venv\Scripts, and running <br>
activate.

### Application requirements

The requirements.txt files will contain all the requirements needed 
for the application. <br>
To install the requirements, simply run in cmd: pip install -r requirements.txt <br/>
Ensure you are located within the root directory and your virtual env. is activated <br/>
Some of the third party modules that will be installed are: 
* flask - Python module used for building web application.
* flask-restplus - flask extension used for developing API.
* Coverage - Python module used in testing, for assessing the quantity of test covered.
* Pytest - Python module for running test.

### Postman
Application used for testing endpoint. <br>
Endpoint available for this api are shown in the table below:

|Requests     |   EndPoint                          | Functionality
|:-----------:|:-----------------------------------:|:--------------:
   GET        |  api/v1/rides                       | Get all Rides 
   GET        |  api/vi/rides/{rideId}              | Get a specific ride
   DELETE     |  api/v1/driver/rideId               | Delete ride          
   POST       |  api/v1/driver/rides                | Add a ride                  
   PATCH      |  api/v1/rides/{rideId}/Request      | Request to join a ride
   PATCH      |  api/v1/driver/rides/rideId/Accept  | Accept the request passengers request
   PUT        |  api/vi/driver/rides/rideId         | Modify ride details
   POST       |  api/v1/register                    | Register users
   POST       |  api/v1/login                       | Login user                       

## Running test

Running test can be done by using unittest, pytest.
To run test you can either run the following commands in cmd:
* coverage run -m unittest
* pytest




    
 
