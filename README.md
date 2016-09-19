## Synopsis

This project is a POC of a monitoring system aimed at alerting in any case of suspicion a baby is left unattended in a car.
The code was developed in the course of a 24 hours hackathon at Beit Hatfutsot by Daniel Grinberg and me.

## General

We build this project on top of an existing code base supplied by EvoThings.
We took a sample app of EvoThings ("TI SensorTag CC2650 & CC2541 Sensors") and added our code to the main index.html file.

In order to deploy our code, one needs to download EvoThings studio to his\hers laptop & the EvoTihngs app to your phone. Please see EvoThings website for details: https://evothings.com/
## Tests

TODO

## Technichal

Right now the code checks to see if we're in an emergency by looking at 2 parameters (values of both can be changed easily - see code in index.html):
Low luminosity
High temperature 

In any case of an emergency, the software sends an SMS to a pre configured number.

For client ID \ secret and for to \ from phone numbers you can mail me at: alon.mannor@gmail.com
