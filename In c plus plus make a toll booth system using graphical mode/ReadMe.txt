Imagine a toll booth at a bridge. Cars passing by the booth are expected to pay a fifty cent . Mostly they do, but sometime a car goes by without paying.The toll booth keeps track of the number of cars that have gone by, and of the total amount of money collected. 

Model this toll booth with a class called tollbooth. The two data items are a type unsigned int to hold the total number of cars, and a type double to hold the total amount of money collected.  A constructor initializes both these to 0. A member function called payingcar() increments the car total and adds 50 cent (0.50) to the cash total. Another function, called nopaycar() , increments the car total but adds nothing to the cash total. Finally a member function called display() displays the two totals.

Include a program to test this class. This program should allow the user to push one key to count a paying car, and another to count a nonpaying car. Pushing the ESC key should cause the program to print out the total cars and total cash in a graphical mode and exit.

IDE and Compiler used : Dev C++ 5.11 and GCC 4.9.2
OS used : Windows 10