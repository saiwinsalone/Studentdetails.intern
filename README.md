# Studentdetails.intern

This Java program is a basic student management system that lets you manage up to 100 student records using arrays and a menu-driven interface.​​
You start by entering the number of students and their details (ID, name, marks). After that, you can use the menu to:

Add Student: Enter a new student's ID, name, and marks. The program checks that the ID is not too long and adds the student if there is space.​​

View Students: See all student records in a formatted table, showing each student's ID, name, and marks.​​

Update Student: Change the name or marks for a student by entering their ID. If the ID is found, the details are updated.​​

Delete Student: Remove a student by ID. The program shifts the remaining records to fill the gap and updates the count.​​

Exit: Ends the program with a message.

Extra details:

The program uses input validation to make sure student IDs are not longer than 15 digits.​​

All operations are done in memory (no database), so data is lost when the program exits.​​

The menu repeats until you choose to exit, so you can manage students as needed.

Sample output:

After entering students, you see their details listed.

The menu lets you add, view, update, or delete students.

When you exit, it prints “Exiting program…
