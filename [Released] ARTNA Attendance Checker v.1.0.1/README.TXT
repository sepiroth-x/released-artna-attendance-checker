========================
ARTNA APP - Attendance Checker v.1.0.1
Developed by: Sepiroth - X (Richard C. Cupal, LPT)

========================
Application Instructions:
========================
Attendance Checker -> This application will separate names from a list into present list and absent list. Also you can add custom notes 
for personal reminders. The application will also capture essential information about the class such as: section, subject & schedule.

1. Install JRE (ignore if JRE already installed)
2. run artna-attendanceChecker.jar
3. load masterlist file (.txt)
4. save masterlist file to any location

========================
Installation:
========================
1. Make sure JRE (Java Run-time Environment is installed in your system)
2. Run the artna-attendanceChecker.jar 


========================
Loading a Master List file:
========================
In the current version, attendance master list should have the following metadata
to ensure correct loading and retrieval of data (list) from the .txt file.
The following essential tags are necessary in order for the app to read the .txt file correctly:

The necessary HEADER TAGS of the masterlist file (.txt):
[section:]
[subject:]
[schedule:]
[type:]

the above tag are the exact symbols being read by the software to load contents of a masterlist file.

Example tag:
[section:2-Loyalty]
[subject:Comp 214 - Basic Programming in C]
[schedule:Monday & Tuesday (5:00 - 7:30pm)]
[type:masterlist]

-- followed by the list of students names---

Note: The above tag must be present inside the .txt file in order for the app to read correctly the file contents.
Please refer to the sample masterlist file attached in this folder or in my github repository: https://github.com/sepiroth-x


==============================
This software is PART of a BIGGER PROJECT ARTNA APP
License: MIT License
Software Developed By: Sepiroth X
Donate via Gcash to support Development: 09150388448

Follow on Github for project updates and view my works: /https://github.com/sepiroth-x
==============================