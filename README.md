**Library Management System**

**Introduction :**
The Library Management System (LMS) is designed to efficiently handle library records, minimizing administrative tasks for librarians. Core functionalities include adding, removing, and viewing the status of books.
**
**Features :**
1. User-Friendly Interface: The system offers a user-friendly interface, facilitating easy management by librarians.
2. Book Management: Librarians can add new books, remove issued books, and display book details through distinct classes.

**Why use Java ?**

Java is chosen for its object-oriented nature, cross-platform compatibility, simplicity, security, and robust features.
**
MVC Architecture :**
The project utilizes the Model-View-Controller (MVC) architectural pattern, organizing code to separate concerns and enhance maintainability.

**Components :**

**Model (com.qsp.lms.model) :**
**- Book.java :**
  - Represents a book with attributes such as name, author, and price.
  - Provides getter and setter methods for accessing and modifying these attributes.
  - Overrides the toString method to offer a formatted representation of the Book object.
**- Library.java :**
  - Represents a library with attributes like name, address, and pin code, along with a list of books.
  - Offers methods to get and set these attributes, and manipulate the list of books.
  - Overrides the toString method for textual representation.

**View (com.qsp.lms.view) :**
**- View.java :**
  - Handles user interface interactions using Scanner for input.
  - Displays a menu of options including adding, removing, updating book prices, searching for books, and exiting the application.
  - Communicates with the Controller to execute user requests.

**Controller (com.qsp.lms.controller) :**
**- Controller.java :**
  - Acts as an intermediary between Model and View.
  - Manages user input and coordinates interactions between Model and View.
  - Provides methods for adding, retrieving, removing, and updating books in the library, as well as exiting the application.

**Usage :**
- The View class provides a menu-driven interface for users to interact with the system.
- Users can choose options to perform various tasks such as adding, removing, updating books, searching for books, and exiting the application.
- The Controller class orchestrates these actions by interacting with the Model to update or retrieve data and updating the View accordingly.

**Conclusion :**
The Library Management System implemented in Java with MVC architecture offers a structured approach to managing library records, enhancing efficiency and ease of use for librarians.
