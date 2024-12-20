# 24836_Julius_Nayebare_OOP_Group-E-Sunday-Evening
Handling Exceptions - Summary of my Submission

•	Checked Exceptions

These are exceptions checked at compile time, meaning the programmer must handle them with a try-catch block or declare them using throws.
1.	IOE Exception: Occurs when there is an issue with Input/output operations, such as reading a non-existent file.
2.	FileNotFoundException: A specific type of IOException thrown when trying to access a file that doesn't exist.
3.	EOFException: Happens when attempting to read beyond the end of a file, typically during file streaming.
4.	SQLException: Thrown for database-related issues, such as connecting to a non-existent database or executing invalid SQL commands.
5.	ClassNotFoundException: Occurs when trying to load a class at runtime that cannot be found in the class path.
________________________________________
•	Unchecked Exceptions
These exceptions occur at runtime and are not checked by the compiler, so handling them is optional.
6.	Arithmetic Exception: Happens during arithmetic operations, like division by zero.
7.	NullPointerException: Thrown when trying to access methods or fields on a null reference.
8.	ArrayIndexOutOfBoundsException: Occurs when trying to access an array element at an invalid index.
9.	ClassCastException: Thrown when performing an invalid type cast between incompatible types.
10.	IllegalArgumentException: Happens when a method is passed an argument that is inappropriate or invalid.
11.	NumberFormatException:
Occurs when attempting to convert a malformed string into a numeric value, such as parsing "abc" into an integer.

