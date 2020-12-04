#How to use this repository

Install all dependencies (testing dependent packages)
"npm install"

Run the main program
"node index.js"

Run all tests cases
"npm test test/run.testcases.js"


Problem Statement:
-----------------------

● Registration numbers of all cars of a particular colour. <br />
● Slot number in which a car with a given registration number is parked. <br />
● Slot numbers of all slots where a car of a particular colour is parked.<br />


Inputs:
----------------------
create_parking_lot 6 <br />
park KA-01-HH-1234 White <br />
park KA-01-HH-9999 White <br />
park KA-01-BB-0001 Black <br />
park KA-01-HH-7777 Red <br />
park KA-01-HH-2701 Blue <br />
park KA-01-HH-3141 Black <br />
leave 4 <br />
status <br />
park KA-01-P-333 White <br />
park DL-12-AA-9999 White <br />
registration_numbers_for_cars_with_colour White <br />
slot_numbers_for_cars_with_colour White <br />
slot_number_for_registration_number KA-01-HH-3141 <br />
slot_number_for_registration_number MH-04-AY-1111 <br />

Outputs: 
------------------
Created a parking lot with 6 slots <br />
Allocated slot number: 1 <br />
Allocated slot number: 2 <br />
Allocated slot number: 3 <br />
Allocated slot number: 4 <br />
Allocated slot number: 5 <br />
Allocated slot number: 6 <br />
Slot number 4 is free <br />
Slot No. Registration No <br />
Colour <br />
1 <br />
KA-01-HH-1234 <br />
White <br />
2 <br />
KA-01-HH-9999 <br />
White <br />
3 <br />
KA-01-BB-0001 <br />
Black <br />
5 <br />
KA-01-HH-2701 <br />
Blue <br />
6 <br />
KA-01-HH-3141<br />
Black <br />
Allocated slot number: 4 <br />
Sorry, parking lot is full <br />
KA-01-HH-1234, KA-01-HH-9999, KA-01-P-333 <br />
1, 2, 4 <br />
6 <br />
Not found <br />
# parking-lot-problem
