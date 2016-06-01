# Final-project
A. Create an abstract class named Rental that is to be used with a snow sports rental shop. The Rental class must have the properties of newModel which takes on the type boolean, and rentalCost which takes on the type double, and rentalNumber which is an identification number as an long integer.These member variables must all be private!

It also must include the following member functions:

1. equals() which returns true if two Rental objects have the same rentalNumber.

2. all of the appropriate get/set methods for each of the above member variables. Make sure to have data validation done on the set methods to prevent invalid/illegal values from being passed into the member variables. (Example: rentalCost should not be allowed to be negative).

3. include an abstract method named lateCharge, that will only be implemented in child classes that inherit the Rental class.

B. Create three children classes that inherit the Rental class, named Ski, Snowboard, and SnowMobile.

The Ski class should have one private member variable named size as an integer that will be used to store the size of the ski in centimeters. Implement the get/set method for this member variable. The abstract method in the Rental class, named lateCharge must be implemented to charge a late charge of 10% of the rental cost. Be sure to include a method named toString to output the data stored in the member variables for this class.

The Snowboard class should have two private member variable named size as an integer that will be used to store the size of the snowboard in centimeters, and another member variable named freestyle as a boolean (true if the snowboard is a freestyle/tricks board, or false if it is not a freestyle board). Implement the get/set methods for these member variables. The abstract method in the Rental class, named lateCharge must be implemented to charge a late charge of 20% of the rental cost. Be sure to include a method named toString to output the data stored in the member variables for this class.

The SnowMobile class should have two private member variable named capacity as an integer that will be used for storing the seating capacity of the snowmobile, and another member variable named vin as a string that stores the snowmobile vin number. Implement the get/set methods for these member variables. The abstract method in the Rental class, named lateCharge must be implemented to charge a late charge of (20+capacity*5)% of the rental cost. Be sure to include a method named toString to output the data stored in the member variables for this class.

C. Create JUnitTest to test each implemented method in the Ski, Snowboard, and SnowMobile classes. The list below is the minimums for the test cases for each of the child classes:

Ski:

1. equals() method

2. newModel ( test get and set )

3. rentalCost ( test get and set )

4. rentalNumber ( test get and set )

5. size ( test get and set )

6. lateCharge - make sure it adheres to the specifications above.

7. toString ( test toString method )

A total of 11 tests for Ski class ( tests 1-4 are actually for the Rental class, and will not need to be repeated for Snowboard and SnowMobile class test )

Snowboard:

1. size ( test get and set )

2. freestyle ( test get and set )

3. lateCharge - make sure it adheres to the specifications above.

4. toString ( test toString method )


A total of 6 tests for Snowboard class

SnowMobile:

1. capacity ( test get and set )

2. vin ( test get and set )

3. lateCharge - make sure it adheres to the specifications above.

4. toString ( test toString method )


A total of 6 tests for SnowMobile class

This portion of the final exam will be due no later than 5:59PM on June 2nd, 2016 and worth 100 points of the 200 for the entire final. Remember on the evening of June 2nd, 2016, we will be having the written portion of the final exam then. Be sure to include a well documented PSP Spreadsheet with your time accurately logged!

This is part of the Final Examination, so rules of Academic Honesty will be strictly enforced.
