# Address Book Project

## Overview

The Address Book Project is a console-based application written in C. It helps you store and manage contacts by keeping track of names, telephone/mobile numbers, and email addresses. This project focuses on using standard I/O for operations like adding, searching, editing, and deleting contacts. 

This project is designed to enhance your understanding of various C programming concepts such as command-line arguments, input parsing, file operations, etc. It does not use Abstract Data Types (ADTs) like linked lists, as it sticks to C's basic features.

### Advanced Version
In the advanced version, the application can be optimized further using ADTs and more sophisticated search algorithms for optimal resource usage.

## Features

The Address Book project has the following features:

### 1. Add Contact
- Add a new contact by specifying the username.
- Add multiple phone numbers to the contact.
- Add multiple email addresses to the contact.

### 2. Search Contact
- Search for a contact by name.
- Search for a contact by phone number.
- Search for a contact by email address.

### 3. Edit Contact
- Edit the contact's name.
- Edit the contact's phone number.
- Edit the contact's email address.

### 4. Delete Contact
- Delete a contact by name.
- Delete a contact by phone number.
- Delete a contact by email address.

### 5. List All Contacts
- Display all contacts stored in the address book.

### 6. Save the Address Book
- Save the current state of the address book to a file for future use.

### 7. Exit the Application
- Exit the application while optionally saving the current state of the address book.

## Project Implementation

The Address Book project is implemented using the following C programming features:

- **Command-line Arguments**: The application takes input from the user to perform various operations.
- **Input Parsing**: The input from the console is parsed and used to execute the corresponding operations.
- **File Operations**: Contacts are saved and loaded from files, making the data persistent across application sessions.
- **Error Handling**: The application includes basic error handling for invalid input, missing contacts, and other user mistakes.

## Usage

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Compile the C program:
    ```bash
    gcc address_book.c -o address_book
    ```
3. Run the program:
    ```bash
    ./address_book
    ```

## Future Enhancements

The following advanced features can be added to the project:

- Implementing ADTs (e.g., linked lists) for better memory management and faster access.
- Adding more advanced search algorithms for optimized performance.
- Implementing a GUI version of the Address Book.
- Allowing export/import functionality in different formats such as CSV, JSON, etc.

## License

This project is licensed under the MIT License.
