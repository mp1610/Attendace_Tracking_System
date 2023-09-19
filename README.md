# Attendace_Tracking_System

This project uses Python and SQL to pre-process attendance data, to develop a simple attendance tracking system for the senior tutor of a department. The tutor should be able to check whether students attend lectures, lab sessions and other activities of modules in the current semester.

Firstly, python script (CW_Preporcessing) is written to clean the datasets and to create an SQLite database within which dataframes can be saved so they can be used in different ipynb files.

Next, a python program 'Student_Att' is written to find out the attendance record of a student. The code asks the user to input a student ID and a module code. It will then filter through the dataset to obtain the weekly attendance % for that student and create a bar plot that represents this.

The next python code 'Module_Att'  displays the attendance of a module in a particular
week. Given module code and week number, the program produces a list
which shows attendance of each session in the week. The attendance of each
session is colour coded to highlight poor and good attendance.

'Poor_Att' is used to analyse the attendance records in the database and find out
a list of students with poor attendance. If a students average attendance is much lower than the class average, the student ID as well as their weekly attendance over the module is added into a new dataframe for poor attendance students.

Finally, a GUI is created that creates a hub to apply all of these different python programs and generate several new dataframes and graphical visualisations presenting student attendance data.

All codes and datasets are available in this repository which shows the many steps involved in completing this project.
