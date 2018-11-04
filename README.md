# PARKING LOT
--------------
Its an application for automated parking lot management. The incoming vehicles will always be allocated a parking slot nearest to the entry.

Code specs
----------
Code is written in Java. JDK 8 is a prerequisite to run this code.

How to Invoke
---------------
Download the file ParkingLot.zip from Git and extract it.
Invoke the application by running the command "java parking_lot" from the location "ParkingLot/out/production/ParkingLot"
This application supports an interactive command line based shell. It can also accept a file passed as a command line parameter with batch commands in it. 

Functionalities
---------------
Run this application by 
The following are the example of commands supported:
$java parking_lot //runs the program
create_parking_lot, 6 //creates a parking lot with 6 slots
park KA-01-HH-1234 White //allocates a parking slot number closest to the entry 
leave 4 //Free up the parking slot number 4
status //Get the status of the parking lot 
registration_numbers_for_cars_with_colour White //utility functions that does as the name suggests
slot_numbers_for_cars_with_colour White  //utility functions that does as the name suggests
slot_number_for_registration_number KA-01-HH-1234  //utility functions that does as the name suggests
exit //exit the program




