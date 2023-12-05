# Library-Management-System

This Python code implements a simple library management system where users can view available books, borrow, return, and donate books. The program is organized into two classes: Library and Student. The main method interacts with these classes to provide library functionalities through a console-based interface.

**Key Components and Functions:**

**Library Class:**

Initializes with a list of available books.
Provides methods to display available books, borrow books (removing from the available list), return books (adding back to the available list), and donate books (adding to the available list).
Keeps track of borrowed books in the track list.

**Student Class:**

Provides methods for a student to request, return, and donate books.
These methods take user input for book-related actions.

**Main Method:**

Initializes an instance of the Library class (IU_Library), a Student instance, and an empty track list to keep track of borrowed books.
Displays a welcome message and a menu of options for users.
Enters into an infinite loop to repeatedly prompt the user for actions.
Options include listing available books, borrowing, returning, donating books, tracking borrowed books, and exiting the library.
Utilizes exception handling to catch invalid inputs and display appropriate messages.
The program continues to run until the user chooses to exit.
