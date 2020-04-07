# CRISIL
A Python programming excercise.

REQUIREMENT:
------------
Given an array of integer values select the smallest integer value which is not in
the list and is not a sum of any combination of integers in the list:

INPUT:
------------
Input #1: [1, 2, 5, 7] - Output should be 4
Input #2: [1, 2, 2, 5, 7] - Output should be 18

SOLUTION:
------------

STEP #1/. Create list containing a lists, each of which is a possible combination
               of any elements in the user input
               
STEP #2/. Create a new list where each element is the sum of all elements in each
               element of the list created in step 1/.
               
STEP #3/. Create a set containing elements of both list above

STEP #4/. Get minimum and maximum value of the set created in Step #3

STEP #5/. Generate range of values between MIN() and MAX() in Step #4.

STEP #6/. Loop over range values pick the smallest that does not exist
                in the set or if not found select MAX() value of set + 1
                
REMARKS:
------------
The code makes no attempt to generalize input, optimize for performance or cater to specific Python version.
