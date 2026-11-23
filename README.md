# Python-Portfolio
Python programs from Structured Problem Solving coursework: Input validation, Loops, Functions and lists. Built using Google Colab.
## Program Details

### Class Vote Counter (HW9-2)
Counts votes for four candidates as they're entered one at a time, then prints the final totals. Any entry that isn't a valid candidate number is rejected with a message, so bad input never changes the count. Uses parallel lists to store candidates and votes, and a sentinel loop that runs until the user enters Q.

### Largest & Smallest Value Marker (HW9-1)
Collects any number of values from the user and stores them in a list. When the user quits, it prints every value and marks the largest and smallest. Shows list handling, built-in max/min functions, and conditional output inside a loop.

### Simple Calculator (HW8-2)
Takes two numbers and an operator, then adds or subtracts them through separate functions. Unknown operators are caught and reported instead of crashing the program. Shows how functions with return values break a program into reusable parts.

### String in a Box (HW8-1)
Draws an asterisk border around any text the user enters, sizing the box automatically to the text's length. Handles empty input with a clear message. Shows function design and string-length calculations.

### Multiplication Table (HW7-3)
Prints the multiplication table from 1 to 10 for a number the user picks. Input outside the 1–10 range is rejected before any output, an example of range checking. Uses a for loop over a range.

### Even or Odd (HW7-2)
Tells the user whether each number they enter is even or odd, and keeps running until they enter -1. Uses the modulo operator and a while loop with a sentinel value.

### String Inverter (HW7-1)
Reverses any string the user types, character by character. Builds the result manually with a for loop instead of a built-in shortcut, to show how string iteration works.

### Income Tax Calculator (HW6-2)
Calculates income tax across six progressive brackets, from 1% up to 6%. Each bracket adds its base amount plus a percentage of the income above its threshold. Shows multi-branch if/elif logic and formatted currency output.

### Unit Conversion (HW5-4)
Converts a distance in meters to miles, feet and inches, rounded to two decimal places. Shows numeric input, arithmetic with conversion constants, and f-string formatting.

### Large Letters (HW5-3)
Prints the word HELLO in large block letters made of asterisks. Each letter is stored once as a constant and reused, so the repeated L is defined only once.

### Birthday List (HW5-2)
Prints a neatly aligned two-column list of names and birthdays. Shows output formatting and spacing.

### Program Header (HW5-1)
Prints a standardized header with the author, date, course and assignment. Every later program in this portfolio uses the same format.
