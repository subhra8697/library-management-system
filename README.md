# __Library Management System__
This Library Management System (LMS) is developed using C++ with MySQL integration. It provides comprehensive functionalities to manage a library's resources including books, members, borrowing, returning, and data storage and retrieval via a MySQL database.

## __Features__
* Book Management: Add, remove, update, and search books in the library inventory. All book data is stored in the MySQL database.
* Member Management: Add, remove, update, and search library members. Member information is stored in the MySQL database.
* Borrowing: Allow members to borrow books. Borrowing transactions are recorded in the MySQL database.
* Returning: Manage the return of borrowed books. Update the status of returned books in the MySQL database.
* Fine Calculation: Automatically calculate fines for late returns based on the return date. Fines are recorded in the MySQL database.
* MySQL Integration: Seamless integration with MySQL for efficient data storage and retrieval.
* User-friendly Interface: Easy-to-use interface for both library staff and members.

## __Requirements__
* C++ compiler (C++11 standard or later)
* MySQL server
* MySQL Connector/C++ library

## __Usage__
* Clone or download the repository.
* Install and configure MySQL server.
* Install MySQL Connector/C++ library.
* Compile the source files using a C++ compiler with appropriate flags to link MySQL Connector/C++ library.
* Run the compiled executable file.

## __Database Setup__
* Create a MySQL database for the library management system.
* Import the provided SQL script to create necessary tables and populate initial data.

## __How to Use__
* Main Menu: Upon running the program, you'll be presented with a main menu.
* Options: Choose an option from the main menu to perform various operations such as book management, member management, borrowing, returning, generating reports, etc.
* Follow Instructions: Follow the instructions provided by the system to perform specific tasks.
* Exit: Choose the exit option to close the program.

## __Contributing__
Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to create a pull request.

## __License__
This project is licensed under the [MIT License](./LICENSE) - see the LICENSE