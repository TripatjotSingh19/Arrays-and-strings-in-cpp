# Arrays and Strings in C++
# Aim
To study and implement C++ Arrays and Strings using practical programs for traversal, searching, reversal, and manipulation.

# Apparatus
VS Code or Online C++ Compiler

# Theory
# Arrays in C++
An array is a collection of variables of the same type stored at contiguous memory locations. It is used to store multiple values under a single name and can be accessed using an index.

➔ Declaration:
int arr[5]; // Declares an array of 5 integers
➔ Initialization:
int arr[5] = {1000, 2, 3, 17, 50}; // Assigns values at declaration
➔ Accessing Elements:
int x = arr[2]; // Accesses the 3rd element (index starts from 0)
Key Points:

Arrays are zero-indexed: the first element is at index 0.
Elements are stored in consecutive memory locations.
Useful for storing lists of data like numbers, names, marks, etc.
# Strings in C++
A string is a sequence of characters used to store and manipulate text. In C++, the string class (from <string>) simplifies handling text.

➔ Declaration and Input:
string name;
cin >> name; // Input a single word
➔ Common Operations:
string full = name1 + name2; // Concatenation
int len = name.length();     // Length of string
# Algorithms (Arrays)
1. Array Declaration and Traversal
Declare an array of fixed size.
Initialize the array using user input or hard-coded values.
Traverse the array using a loop and print each element.

2. Input and Output of Array
Read the size of the array.
Use a for loop to input values into the array.
Use a for or range-based loop to print all values.

3. Reverse an Array
Read n elements into an array.
Create another array to store reversed values.
Copy elements from the original array in reverse order.
Print the reversed array.

4. Search an Element in Array
Input an array of n elements.
Input a number to search.
Traverse the array.
If a match is found, print index and count occurrences.
Algorithms (Strings)

1. Concatenation of Strings
Input two strings.
Use + operator to concatenate.
Output the result.

2. Palindrome Check
Input a string.
Compare characters from start and end moving towards center.
If all characters match, print "Palindrome".
Else, print "Not a Palindrome".
# Conclusion
In this experiment, we explored fundamental operations using arrays and strings in C++. Arrays provided an efficient way to store and process collections of data, while strings enabled manipulation of textual input. Through implementation of basic algorithms like reversal, searching, and average computation, we gained practical understanding of loop structures, indexing, and standard library usage in C++. This experiment built a strong foundation for future work in data structures and problem solving using C++.
