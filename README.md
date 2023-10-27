# Library Management System with Hash Table

This is a C++ program that implements a simple Library Management System using a Hash Table. The system allows users to manage a list of students and the books they have issued.

## Table Of Content

- [Introduction](#introduction)
- [Components](#components)
- [Usage](#usage)
- [Example](#example)
- [Requirements](#requirements)


## Introduction

The Library Management System uses a Hash Table to efficiently manage and search for student records and their issued books. It offers the following functionalities:

- Display a list of available books.
- Issue a book to a student.
- Return a book.
- Search for a student and the book they have issued.
- Display the current state of the Hash Table.

## Components

The program is implemented with the following key components:

- `HashTable` class: Represents the Hash Table and its operations.
- `books` and `book_id` arrays: Store book names and their corresponding IDs.
- `checkPrime` and `getPrime` functions: Calculate prime numbers for table size.
- `hashFunction` method: Determines the index for a given key.
- `displayBooks` method: Displays the list of available books.
- `bookThere` method: Checks if a book is available for issuing.
- Menu-driven interface: Users can choose options to interact with the system.

The program provides a user-friendly menu-driven interface. When you run the program, you will see a menu with the following options:

1. Display Books
2. Issue Book
3. Return Book
4. Search for Student
5. Display Hash Table
6. Exit

You can select an option by entering the corresponding number. Depending on your choice, the program will display a list of books, allow you to issue or return a book, search for a student's issued book, display the Hash Table, or exit the program.

## Usage

1. Compile and run the program.
2. Follow the menu options to interact with the Library Management System.
3. Use the provided book IDs to issue or return books.

## Example

Here's an example of using the program:

1. Display Books
   - You can view a list of available books and their IDs.

2. Issue Book
   - Enter the student's PRN.
   - Enter the book's ID to issue.
   - If the book is available, it will be issued to the student.

3. Return Book
   - Enter the student's PRN to return the book.

4. Search for Student
   - Enter the student's PRN to find the book they have issued.

5. Display Hash Table
   - View the current state of the Hash Table.

6. Exit
   - Choose this option to exit the program.

## Requirements

- C++ compiler (e.g., g++)
- Command-line environment
