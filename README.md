# Project_1_DS

Polynomial Calculator
January 2021 - Intro to Data Structures with Java
Project 1B

TEAM SIX
Rachael Mallinson
Sofia Nikas
Aleksis Martin

Design Explanation

First we created a Term class defined by 2 integers (the coefficient and the exponent). Then, we split the polynomial entered by the user - isolating each string separated by the “+” sign. By doing this, we were able to identify the coefficient and exponent in each string and create Terms . The role of our first ArrayList is to hold those Terms . 
Then we used this ArrayList of Terms to combine any coefficients with the same exponent.  We accomplished this by iterating through the new list and comparing each term’s exponent to every other term, to see if they needed to be combined. 
The last step was to output the resulting added polynomial into a new sorted ArrayList in decreasing order by exponent and output that string to the console in a  user-friendly fashion.
