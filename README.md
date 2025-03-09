# Library Management System

## Introduction
This project focuses on manipulating Strings in Java through practical tasks related to a **Library Management System**. The goal is to develop functionality for better organization and cataloging of book inventories. This exercise demonstrates key concepts, such as checking String lengths, shortening Strings, and searching for specific parts of a String.

## Context
Riley, the developer of this system, faces challenges in handling book titles that are too long to display correctly. To address this, the project includes:
1. Checking the length of book titles.
2. Shortening titles longer than 20 characters.
3. Searching for specific words within a book title.

## Features and Functionality
1. **Check Book Title Length**:
   - Verify if book titles exceed 20 characters.
   - Use the `substring()` method to shorten titles when necessary.

2. **Search for a Word in a Book Title**:
   - Leverage the `contains()` method to search for specific words or characters in titles.

3. **Demonstrate String Methods**:
   - Utilize Java methods like `length()`, `substring()`, and `contains()` to manipulate Strings effectively.

## Steps to Implement
### Step 1: Declare and Initialize a Variable to Check Its Length
- Create a variable `bookTitle` in the `main` method and assign a title to it.
- Determine the title's length using the `length()` method.

### Step 2: Shorten Titles Exceeding 20 Characters
- Check if the title exceeds the 20-character limit.
- If so, apply the `substring()` method to reduce its length to 20 characters.

### Step 3: Search for a Specific Word in the Title
- Declare and initialize a `String` variable `searchWord`.
- Use the `contains()` method to check for the presence of a word in the book title.

## Reflection Point: Understanding Arrays
Strings in Java are represented as arrays of characters (`char` data type). Understanding arrays provides a strong foundation for effectively working with Strings and manipulating data in Java.

## Conclusion
This project demonstrates real-world applications of String manipulation in Java programming. By completing this exercise, you will strengthen your understanding of key methods and their practical uses in managing data efficiently.

## Software Used
- **IntelliJ IDEA**: The integrated development environment used for coding and executing the program.
