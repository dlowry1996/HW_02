# HW_02
Hi All - I am taking a class through edX, Introduction to Object-Oriented Programming with Java I: Foundations and Syntax Basics. I am stuck on HW 02, here is the prompt: 
For homework 02, you will be creating a calculator that can perform the following operations: add, subtract, multiply, divide, and alphabetize. The operations work as follows:

Add - takes two integers, adds them and prints out the result
Subtract - takes two integers, subtracts the second entered integer from the first and prints out the result
Multiply - takes two doubles, multiplies them and prints out the result to two decimal places
Divide - takes two doubles, divides them and prints out the result to two decimal places
Alphabetize - takes two Strings of only letters, and tells which word comes before the alphabetically
Your program will be named Calculator.java. It should work as follows:

Print out the list of operations for the user.
Prompt the user to enter an operation. If at any point an invalid input is given, the program should terminate.
Perform the chosen operation and print the correct output.
If the user is performing an add/subtract operation, prompt the user to enter two integers.
If the user is performing a multiply/divide operation, prompt the user to enter two doubles.
If the user is performing an alphabetize operation, prompt the user to enter two Strings NOT integers.
The program should end after the operation is performed.
Note that 0 should not be in the denominator if you are dividing. If a 0 is in the denominator, terminate your program. For the multiply and divide operations, format your output using printf.

Your program is required to have at least one switch statement and one if/else statement.

For the alphabetize operation, you will be using a method that compares two strings lexicographically, and returns an integer depending on which String is larger. If a 0 is returned, both Strings are lexicographically equal. A positive integer is returned if the first string is lexicographically greater than the second string, or else the result would be negative.

Hint: You'll likely use one of the String methods that takes a substring of a String. Refer to the String API if needed.

When prompting for integers, doubles, or Strings, a single space will serve as a divider between the two inputs. Remember that when performing multiply/divide operations on doubles, the answer should only include two numbers after the decimal point.

Example Outputs. User input is bolded. Please make sure to follow the exact formatting as shown in the pdf.

List of operations: add, subtract, multiply, divide, and alphabetize.
Enter an operation: add  
Enter two integers: 3 4 
Answer: 7
List of operations: add, subtract, multiply, divide, and alphabetize. 
Enter an operation: subtract 
Enter two integers: 5 8  
Answer: -3
 
List of operations: add, subtract, multiply, divide, and alphabetize. 
Enter an operation: multiply  
Enter two doubles: 3.561 7.63 
Answer: 27.17
List of operations: add, subtract, multiply, divide, and alphabetize.  
Enter an operation: divide  
Enter two doubles: 12.0 3  
Answer: 4.00
List of operations: add, subtract, multiply, divide, and alphabetize.`  
Enter an operation:` alphabetize  
Enter two Strings:` "Hello" "World"  
Answer: Hello comes before World alphabetically.
Rubric
[100] Calculator.java
[10] Prompts user to type in an operation
[10] Prompts user for two integers for add/subtract operations
[10] Prompts user for two doubles for multiply/divide operations
[10] Prompts user for two Strings for compare operation
[10] Uses at least one switch case and if/else statement
[30] Prints calculation results correctly
[10] Prints multiplication and division results correctly with two decimal places using printf
[10] Prints add and subtract results correctly in int
[10] Prints compareTo results correctly
[20] Terminates when incorrect input is provided
[10] Terminates when no invalid operation is put
[10] Terminates when 0 is in the denominator
Allowed Imports
To prevent trivialization of the assignment, you may only import java.util.Scanner.

Feature Restrictions
There are a few features and methods in Java that overly simplify the concepts we are trying to teach or break our auto grader. For that reason, do not use any of the following in your final submission:

var (the reserved keyword)
System.exit
