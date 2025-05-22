# Restaurant-Management-System
The provided C program implements a simple restaurant management system with file handling capabilities. It allows users to add, remove, display, search, sort, save, and load dishes in a menu. The program utilizes concepts of linear search, binary search, insertion sort, and file handling to manage the restaurant menu efficiently. 
## Design and Analysis of Algorithm (DAA) concepts used: 
### Linear Search: 
The program uses linear search to find a dish by name or phone number in the contact list. \
It iterates through the list of contacts to find a match based on the name or phone number. \
The linear search algorithm has a time complexity of O(n), where n is the number of contacts. 
### Binary Search: 
The binary search algorithm is employed to efficiently search for a dish by name in the menu. \
It operates on a sorted array of dishes and repeatedly divides the search interval in half. \
Binary search has a time complexity of O(log n), making it more efficient than linear search for large datasets.
### Insertion Sort: 
The insertion sort algorithm is used to sort the contacts by name after adding a new contact. \
It iterates through the list of contacts and inserts each element into its correct position in the sorted list. \
Insertion sort has a time complexity of O(n^2) in the worst case, making it suitable for small datasets.
### File Handling: 
The program includes functions to save the menu to a file and load the menu from a file. \
It uses file I/O operations to write the menu data to a text file and read the menu data from a text file. \
File handling allows the program to persist the menu data between different program runs.
### Menu Management: 
The program provides a menu-driven interface for users to interact with the restaurant management system. \
Users can add, remove, display, search, sort, save, and load dishes in the menu using the provided options. \ 
The menu management functionality enables efficient manipulation and organization of the restaurant menu.
### User Input Handling: 
The program handles user input for various operations, such as adding, removing, searching, and sorting dishes. \
It utilizes input validation and buffer clearing to ensure accurate and reliable user interactions. \
Proper handling of user input enhances the usability and robustness of the restaurant management system.
