Final Year Attendance Sheet Oral Surgery
This is a web application for tracking and managing attendance for a final year oral surgery class. The entire application is self-contained within a single attendance_sheet.html file, which includes the HTML structure, custom CSS for styling, and JavaScript for all functionality.

Features
Student Roster: A pre-defined list of 125 students with specific roll numbers marked as inactive.

Data Input: Users can input the date, batch name, lecture topic, and faculty name.

Attendance Toggling: Students are marked as "Present" by default and can be toggled to "Absent" by clicking their roll number.

Data Submission: Attendance data can be submitted and sent to a specified Google Apps Script URL.

Export Functionality: Export attendance records as a CSV file or a PDF document.

Local Storage: The last submitted attendance record is saved in local storage for quick access and export.

How to Run
Clone the repository:
git clone [your-repository-url]

Open the file:
Simply open the attendance_sheet.html file in any modern web browser (e.g., Chrome, Firefox, Safari). No server or special setup is required.

Project Structure
attendance_sheet.html: The core and only file of the web application.

README.md: This file, which provides an overview of the project.

.gitignore: Tells Git which files to ignore.