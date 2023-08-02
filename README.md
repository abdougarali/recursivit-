 Project Name (récursivité)
This repository contains a simple and efficient algorithm to check if a given string is a palindrome or not using recursion. 
A palindrome is a sequence of characters that reads the same backward as forward.


The algorithm takes a string as input and recursively checks if it is a palindrome. It follows the following steps:

Base Case: If the string is empty or has only one character, it is considered a palindrome, and the algorithm returns True.



Recursive Case: The algorithm compares the first and last characters of the string.
If they are not the same, the string cannot be a palindrome, and the algorithm returns False.
Otherwise, it removes the first and last characters from the string and calls itself recursively with the updated string.


Return Value: The recursive calls continue until the base case is reached, and the function returns True if all the characters match during the recursive process
, indicating that the input string is a palindrome.
Otherwise, it returns False
