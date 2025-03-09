## Working with Strings
Libray Management System

## INTRODUCTION 
In this lab, you’ll use various methods to manipulate Strings in Java. You will check String length, shorten Strings, and search for specific parts of a String.
Let’s use Riley as an example. Riley has a problem. She is developing a library management system for clients to better organize and catalog their book inventory. However, there is an issue with capturing book titles: when they are too long, they do not display correctly in the management system.
To ensure book titles display correctly, they must be no more than 20 characters long. Riley needs to check the title length and shorten it if it exceeds this limit. Additionally, Riley wants the system to search for specific words in a book title to enhance functionality.
You’ve been provided with the starter code. To help Riley, you must write the necessary code to accomplish the requested tasks. Let’s get started! 

## REFLECTION POINT: UNDERSTANDING ARRAYS
Previously, you learned that an array in Java is a collection of elements of the same type stored in contiguous memory locations. Arrays allow efficient data access and manipulation using an index and help handle multiple values with a single variable. Therefore, a String is a sequence of characters represented internally as an array of the char data type.
Understanding arrays is crucial because it forms the basis of how Strings and other data structures work in Java. By grasping the concept of arrays, you will be better equipped to manipulate data efficiently, as you will be doing in this lab.

## THE GAOL
Help Riley by checking book title lengths, shortening long titles, and searching for specific words in book titles?

## CHECK THE LENGTH OF THE BOOK TITLE
STEP 1: Declare and initialize a variable, then check its length
- Inside the main method, declare a variable name *bookTitle*, and assign a name to it.

STEP 2: Declare and initialize a variable then check its length
- Once you've confirmed the length of *bookTitle*, check if the book title is more than *20* characters long. If it is longer, use the *substring()* method to limit the book title length to *20* characters.

## SEARCH FOR A WORD IN A BOOK TITLE
Riley also wants her system to be searchable, particularly for finding words or characters within book titles. Now you’ll search for a word in the book title you created. 

STEP 3: Find a word in the book title
- Declare and initialize a String variable searchWord. Use the *contains()* method to check if a particular word is present in the book title. 

## CONCLUSION
In this lab, you learned how to use the *length()*, *substring()*, and *contains()* methods in Java to manipulate Strings. You checked the length of a String, shortened a too-long String, and searched for a part of a String—all in the context of Riley's library management system! You saw how manipulating Strings has real-world uses in Java programs. 
Consider working on an example where you can use different String methods. Practice makes perfect, after all!

## Software Used: IntelliJ
