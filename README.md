This C++ project implements a dynamic vector class with a menu-driven interface that allows you to perform various operations on two vectors.

✨ Features
* Display elements of a vector

* Add and remove elements

* Access elements by index

* Insert element at a specific index

* Remove element at a specific index

* Swap two vectors

* Sort the vector

* Move elements within the vector

* Union and intersection of two vectors

* Store only unique elements

* Count frequency of a specific element

* Check if one vector is a subset of another

* Search for an element

* Add and subtract two vectors

* Compare vectors (==, >, <)

* Exit the program

🛠 How to Run

* Clone or Download the project.

Make sure you have a C++ compiler (like g++) installed.

* Compile the project:

g++ main.cpp -o VectorProgram

* Run the executable:

./VectorProgram


📂 Project Structure
* main.cpp — Contains the menu and program flow.

* vector.h — Contains the Vector class template with all the overloaded operators and functions.


🖥 Program Flow
* At start, you are prompted to input the size and elements for Vector 1.

* Menu is displayed repeatedly until you choose to Exit.

* You can perform various operations by entering the number corresponding to the menu option.

Example:

Enter size for Vector 1: 5
Enter elements for Vector 1: 1 2 3 4 5

Menu:
1. Display elements     2. Add an element
3. Remove an element    4. Access at index
...

Enter your choice: 1


Basic understanding of object-oriented programming

📢 Notes
* Exception handling is done for invalid index access and operations.

* Overloaded operators are used for input/output, vector comparisons, addition, and subtraction.

