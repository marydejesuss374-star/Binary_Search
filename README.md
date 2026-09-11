## Laboratory Activity: Recursion

<img width="697" height="423" alt="image" src="https://github.com/user-attachments/assets/f614b46d-066f-4397-ba52-fa31d548303d" />

## Description

This Java program implements a recursive binary search that runs on an array supplied by the user. It first asks for the total number of elements, then the elements themselves, and finally the target value to search for. Before the search begins, the array is sorted in ascending order, since binary search only works correctly on sorted data. As the recursion proceeds, each call outputs the current low, high, and mid values, allowing the search interval to be traced as it narrows down at each step. Once the search completes, the program reports either the index where the target was located, or -1 if the value isn't present in the array.

## Programming language used
Java (developed and tested against Java SE — no external libraries beyond java.util.Arrays and java.util.Scanner from the standard library).

## How to Compile and Run the Program

Save the source code in a file named exactly Binary_Search.java (the filename must match the public class name).
Open a terminal or command prompt in the folder containing the file.
Compile the program:
Run the compiled program:
When prompted, enter:
the number of elements in the array,
each array element (one at a time, in any order — the program sorts them automatically),
the target value to search for. 6.The program will display the sorted array, the recursion trace (if using the trace version), and finally whether the target was found and at what index.

## input and output

<img width="540" height="321" alt="image" src="https://github.com/user-attachments/assets/fa9858ce-7421-4919-a54c-5cff3064d7a3" />

<img width="553" height="305" alt="image" src="https://github.com/user-attachments/assets/98e1bc8c-00bc-4fda-8325-ad6b688676ff" />

## AI Disclosure

I made use of Claude to review my code for any missing characters or letters that might have been left out. I asked it to go through the program and fix anything that appeared incomplete or incorrect.



