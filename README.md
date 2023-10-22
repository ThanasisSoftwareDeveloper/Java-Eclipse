# Java-Eclipse
--------------------------------------------
1st Topic


Voting for the right island for a holiday. There are 20 people voting and each person votes only once. We believe that the candidate islands that these people are invited to vote for are Mykonos, Santorini and Rhodes...

Write a Java program consisting of a class named Holiday and will ask the user to vote for the island that he/she considers the best holiday destination by entering from the keyboard 1 for Mykonos, 2 for Santorini and 3 for Rhodes. It will then print on the screen "You voted for ...", where the name of the island voted for will appear in place of the silences (...) or the message "Your vote was not valid!" in case you enter something other than 1, 2, 3.

After everyone has voted, the program will calculate how many votes each island got and the percentage (%) of the total valid votes, will show the island with the fewest votes and the best holiday destination, i.e. the island with the most votes.

--------------------------------------------
2nd Topic

The Social Security Number (SSN) consists of 11 digits. In particular, the eleven-digit number that makes up the number consists of: 

(a) the first part, which is six digits long and indicates the date of birth (YYYY/MM/YYYY) 
of the person concerned,
(b) the second part, which is a four-digit number indicating the serial number of the person 
concerned in the National Register (for men this number is redundant, for women it is 
even).
(c) the third section, which is a one-digit section and is a control character given by the 
computerised system.

Write a Java program consisting of a class named AMKA and:

It will read an alphanumeric character from the keyboard, 

It will check that the length of the alphanumeric corresponds to a social security number and if not, inform the user with an appropriate message and repeat the step of reading the alphanumeric from the keyboard, 

Using recycling, isolate each character of the alphanumeric using the charAt method, check whether this character is a numeric digit using the isDigit method (and if not, inform the user with an appropriate message and repeat the step of reading the alphanumeric from the keyboard) and store the result in an appropriate table, 

Calculate the age of the person on the basis of the difference between the year of birth and the current year. It is assumed that all individuals were born after 1920,

It will check whether the second part of the social security number is incomplete or redundant and will identify the gender,

It print the age and gender and ask the user if he/she wants to repeat the process or if he/she wants to terminate the program.

Example: To calculate the age based on the first part of the AMA, let's say that the 5th digit of the AMA is 5 and the 6th digit of the AMA is 4. To calculate the year of birth we will have:
1900+5x10+4=1954 and the age will be calculated by the difference between the current year (2020) and 1954 (the person's age will be 66). For example, if the 5th digit of the AMKA is 0 and the 6th digit of the AMKA is 1, to calculate the year we will have 2000+0x10+1=2001, and the person's age will be 19 (2020-2001).

--------------------------------------------
3rd Topic

Create a Java program that contains two classes Window and WindowApp. The first represents a software window and the second is the main class which includes the main method. A window has a name (an lphanumeric), height, width, color (an alphanumeric) and a definition point (it is the top left point of the window). The coordinate values are integer and positive or zero. As an example of a window we can consider the following:
values: height 12, width 8, white color and definition point (0, 0).
Define the Window class to include a constructor to create windows with zero or empty values for the instance variables (depending on the type of each instance variable), with the exception of the value of the 
window name given as a parameter,
a constructor to create windows with values for the snapshot variables given as 
parameters,
a getName method that returns the name of the window,
a getHeight method returning the height of the window,
a getWidth method returning the width of the window,
a getColor method returning the color of the window,
a resize method that takes as arguments 2 new values and changes the height and width 
of the window,
a move method that will move the window's definition point to another point given as an 
argument,
an isSquare method that returns the diagonal of the window if the window is square, 
otherwise -1,
a printWindow method that prints the current state of the window (name, height, width, 
color, definition point).

Define the WindowApp class which will include the main method. The main will:
create two snapshots of the Window, the first with name "w1" and with zero or empty values for the remaining snapshot variables, and the second with the values: name "w2", height 15, width 10, color "blue", and definition point (2, 2),
prints the current state of each window,
moves window "w1" so that its definition point coincides with that of "w2",
prints the current state of 'w1',
changes the data of "w2" to make it twice as wide and half as high,
prints the current state of 'w2'


