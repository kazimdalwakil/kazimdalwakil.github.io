---
layout: page
title: High Security Car Parking System
projectCategory: Computer Interfacing course project
authors: Kazi Md. Al-Wakil, Kawshik Kumar Ghosh, Md. Radip Hassan, Md. Sakib Hossain 
description: This project aims to enhance security in parking lots by ensuring that vehicles cannot be removed without valid authentication. Upon arrival, drivers must enroll their fingerprints, which are stored in a database linked to their vehicle ID. A 16x2 LCD display shows available parking slots and the parking lot's temperature, while a temperature and humidity sensor controls the activation of a heater if needed. The IR proximity sensor detects vehicle presence, and the servo motor opens the gate when there are empty slots. When leaving, the driver must authenticate via the fingerprint sensor. If the fingerprint matches the database, the gate opens, indicated by a green LED; otherwise, the driver is flagged. The system uses an Arduino Uno and various sensors for implementation.
year: 2022
img: assets/img/CSE360.gif
redirect: 
importance: 7
category: Academic
github: https://github.com/kazimdalwakil/Arduino-based-High-Security-Car-Parking-System_Lab-Project_CSE360
show: true
---
It is not new that vehicles get stolen from parking lots even though there are security guards.
Therefore, We are intended to build a prototype where ensuring security will be our
first priority. This project will help us to feel safe knowing that our transportation is safe in the
garage.

The project’s main purpose is to assure people that their vehicle is safe in the garage and can not
be taken out without valid authentication. It will ensure security and safety of the vehicle.
This system can be used in every place where a garage is available. This includes residential
buildings, offices, industrial factories, shopping malls and so on.

Firstly, when a car arrives at the parking lot, the driver of the car will have to give his fingerprint,
which will be stored in the database. A 16x2 LCD Display will be at the gate, 
where it will show how many slots are left to park. In this way, guards do not need to count if the parking lot is
empty or not. Also, the Temperature and Humidity Sensor will help to show the temperature of
the parking lot in the LCD display. This will help the automated system to turn on the heater if
the temperature is too low. While entering all the drivers will have to enroll their fingerprint to
the database. The fingerprint will be stored with an ID. The ID will be representing the car and
the driver. This will help the security officer to identify if the right person with the right car is
leaving the parking lot.

If there are empty slots in the parking lot then the gate will be opened using Servo Motor and
here, we will be using IR Proximity Sensor to sense the presence of the vehicle.
Main part of security comes when a car leaves the parking lot. At that point, the driver will have
to pass the checkpoint where the driver will have to give his fingerprint through the Fingerprint
sensor. If his fingerprint is on the database the Green Led light attached to the gate will be
turned on and he can leave the parking lot. Otherwise, the right person is not taking out a
registered vehicle and will be caught red handed.

The project was done using  Arduino Uno as our interfacing IC

Components Needed:
- Arduino UNO
- IR Proximity Sensor
- Fingerprint Sensor (Optical)
- Temperature and Humidity Sensor (DHT11)
- Servo Motor
- 16x2 LCD i2c Display
- LED light
- Jumpers
- Bred Board

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse360_3.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Block Diagram of the Connections
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse360_1.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Car Parking System Component Connections
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse360_2.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Data Flow
</div>


You can find more about the project <a href="https://github.com/kazimdalwakil/Arduino-based-High-Security-Car-Parking-System_Lab-Project_CSE360">here.</a>
