# Python Essentials II - Assignment

- Part I: Practice with `containers`  
- Part II: Practice with `control flow`

HINT: for user input you may use `input` or you may provide input via command line arguments, which is more common in 
in practice.  Any of the following can be used.

- [sys.argv](https://docs.python.org/3/library/sys.html#sys.argv)
- [getopt](https://docs.python.org/3/library/getopt.html)
- [argparse](https://docs.python.org/3/howto/argparse.html)

## Instructions

We'll be working through problems designed to get more practice with the concepts covered during the python-2 lesson.

## Part 1 - Practice with `containers` 

### QUESTION 1

Write a script that takes as input a string.  Convert the string to lowercase and return to the user the 
letters in the alphabet that were not provided as input.

### QUESTION 2 

Write a script creates a simple [Substitution Cipher](https://en.wikipedia.org/wiki/Substitution_cipher).  
To do this you will need to create a key that specifies a letter it encodes.  A simple substitution cipher would be to 
let each letter of the alphabet correspond to a number.  Your final script should first ask the user to if they are 
encoding or decoding.  Then it should return the appropriate encoded or decoded answer.

## Part II - Practice with control flow

### QUESTION 3

Write a script that removes all the vowels in a user inputted string

### QUESTION 4 

Write a script that accepts a user inputted string.  It then checks whether the string contains characters or is 
numeric.  It prints that number and the Python data type it was cast to.

### QUESTION 5

Write a script that computes the sum from 0 to a user inputted number.

### QUESTION 6

Write a script that creates a list containing only the numbers divisible by a user inputted number that are between 0 
and a user inputted number (**Hint**: Use `input()` twice to get both of the user inputs).  Provide meaningful 
exception handling.

### QUESTION 7

In another script have the user input two numbers.  Given the two numbers output a list of multiples of that 
span the interval between each of the numbers. For example, given the numbers 4 and 20, your script should print the 
numbers 4, 8, 12, and 16.  This should occur even if the input were (20,4).

### QUESTION 8

Write a script that determines whether or not a user inputted number is a 
[prime number](https://en.wikipedia.org/wiki/Prime_number) and prints 
'The number you inputted is (not) a prime number.' depending on what your script finds.  Things to think about:

How do you check if a number is divisible by another number?
What numbers are a prime number divisible by?
How do you check all of the numbers a number could be divisible by (Hint: use a loop)?
When do you stop the loop?

### Question 9 

Write a script that will continually prompt the user for a set of three things to be separated by commas. The first two 
things will be (x, y) coordinates of the word that follows (the word will be the third thing). So the user will input a 
string that is formatted like x, y, word. Your script will use the string to build a dictionary with the first two 
inputs (i.e. the (x, y)) from each string as keys to a dictionary, and the third input (the word) as the value for that 
key. The script will continually prompt the user to input strings in this format until the user inputs nothing 
(i.e. hits enter with no input). After building the dictionary, your script should allow the user to query the 
dictionary it built by accepting strings of the format x, y. It should check if the coordinate is in the dictionary, and 
if it is return the corresponding word. If it isn't, it should print Coordinate not found. This should continue until 
the user inputs the letter q, at which point the script should exit.

### Extra Credit

Improve your cipher by letting each ascii character be represented by a list of random characters.  You should also 
decouple your encode and decode scripts into two separate scripts.  
