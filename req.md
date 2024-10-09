
PROBLEM STATEMENT AND REQUIREMENTS

1. Generate a program to store the data of 58 students with any of the 5 properties.
2. The 5 properties used are:-
     [a] Name 
     [b] USN (USN should be a combination of both digits and character with exactly 10)
     [c] Gender (Only single character M/F)
     [d] Dob (Format used is dd/mm/yyyy).
     [e] Mobile number (Mobile number should be exactly 10 digits)
	 - Mobile number and USN should be unique.
- All the constraints should be accurate.
3 The program must run in all extreme conditions.

THE REQUIREMENTS USED TO CODE THE PROGRAM

Student Data Storage
The system must store details for 58 students, with each student having the following information:

Name
USN (A mix of letters and numbers, exactly 10 characters long, must be unique for each student)
Gender (Either 'M' for Male or 'F' for Female)
Date of Birth (In the format DD/MM/YYYY)
Mobile Number (Exactly 10 digits, must be unique for each student)
Data Validity

The system must ensure that no two students have the same USN or mobile number.
All data must follow the correct format (e.g., 10-character USN, correct gender format, etc.).
Handling Extreme Cases
The system should handle any situation, like incorrect input or missing information, without failing.

File Storage
All student information should be saved in a text file to ensure the data is not lost when the system is closed.
																	



[1] Adding a Student
When you choose to add a student:
•	The system will prompt you to enter the student's ID, name, age, grade and mobile number.
•	This information is stored in memory (for example, in an array or a list of students).
•	Each student will have a unique ID to differentiate them from others.
[2] Deleting a Student
When you want to delete a student:
•	The system will ask for the ID of the student you want to remove.
•	It will search through the list of students to find a match.
•	If the student with the given ID is found, their record will be deleted by removing their entry from the list.
•	The remaining student records will shift to fill the gap left by the deleted student.
[3] Displaying Students
When you choose to display students:
•	The system will show a list of all students currently stored.
•	For each student, it will display their ID, name, age, and grade.
•	If there are no students in the system, it will notify you that the list is empty.
[4] Updating a Student
When you want to update a student's information:
•	The system will ask for the ID of the student you wish to update.
•	It will search the list to find the student with the matching ID.
•	Once found, it will prompt you to enter new details such as the student's name, age, or grade.
•	The student’s information will be updated with the new data you provide.
[5] Exiting the Program
When you choose to exit:
•	The system will stop accepting input and close the program.
•	Before exiting, it can optionally save the data to a file, so that any updates or added students are not lost when you reopen the program.

