# Read-N-Inputs

Input: 3

Output:8
11
25

Question: Read N Inputs

Given an integer N, write a program which reads N inputs and prints them.

Input:

The first line of input will contain a positive integer, N.

The following N lines will contain an integer in each line.

Output:

The output should be N lines, containing an integer per line.

Example:

For example, if the given N is 3, then read the inputs in the next 3 lines and print them. If the given input integers in the next three lines are 8, 11, and 25, the output should be

Approach:
To solve this problem, we will follow these steps:

Read the number of inputs (N) from the user.

Read each input and print it.

Step-by-Step Explanation:

Step 1: Read the number of inputs

First, we need to read the number of inputs (N) from the user. We can use the input() function to read the input and int() to convert it into an integer.

Step 2: Read and print each input

Now, we will create a loop that will run number_of_inputs times. In each iteration of the loop, we will:

Read an input using the input() function and convert it into an integer using int().
Print the input using the print() function.
Increment the counter by 1.
