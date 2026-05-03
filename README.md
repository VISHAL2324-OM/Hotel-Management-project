
# Hotel-Management-System (Java)
A robust, console-based application designed to manage hotel operations, including room bookings, food ordering, and automated billing. This project was developed as part of my transition from Electrical Engineering into Software Engineering, focusing on core Java principles and system design.
# Key Technical Features
## Object-Oriented Programming (OOP): ####Utilizes inheritance (Doubleroom extends Singleroom) and encapsulation to manage complex data structures.

Serialization (Data Persistence): Implements Serializable to save the current state of the hotel (bookings and guest records) into a backup file. This ensures data is not lost when the program closes.

Multithreading: Features a background thread (via the Runnable interface) that handles data backups asynchronously, ensuring the user experience remains smooth and uninterrupted.

Exception Handling: Includes custom exception handling (e.g., NotAvailable) to manage room availability and prevent double-bookings.
# Tech Stack
Language: Java
Concepts: File I/O, Multithreading, ArrayLists (Collections Framework), and Inheritance

