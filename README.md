# SD-3101 [Crime Record Management System]

![Picture1](https://github.com/user-attachments/assets/1760d054-346a-46f7-99a2-6d60cb6830b3)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Chagelog](#changelog)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Introduction
Welcome to the Crime Record Management System repository! This project encompasses three user interfaces: CID, admin, and officer. Employing PHP, HTML, JavaScript, CSS, and MySQL, it offers efficient crime data management. Seamlessly handle records and interactions within the law enforcement ecosystem through this comprehensive system.

## Project Overview
This repository hosts a comprehensive Database Management System (DBMS) project aimed at enhancing crime record management and analysis. Our project is designed to streamline the process of recording, organizing, and analyzing criminal activities, ensuring a more efficient and data-driven approach for law enforcement agencies.
- enhancing crime record management and analysis.
- streamline the process of recording, organizing.
- analyzing criminal activities, ensuring a more efficient and data-driven approach for law enforcement agencies.

## Objectives
We believe that efficient crime record management is crucial for effective law enforcement, and our "Crime Record Management System" project is a step in that direction. By combining cutting-edge technologies and a user-centered approach, we aim to revolutionize the way crime data is handled and analyzed. We invite you to explore, contribute, and collaborate to make our criminal justice system more effective and data-driven.

## Features
main features of the project:
- Feature 1: Admin

Admin Dashboard
View Staff List
Assign case to CID Officer
Manage Account.

- Feature 2: NCO

NCO Dashboard
Register a Complain
View list of complains
View details of case investigation
Assign a case CID Officer
Manage Account/Change Password.

- Feature 3: CID

CID Dashboard
View list of cases assigned
View details of case investigation
Write a report on the case being investigated
Manage Account/Change Password.


## Technologies Used
Our project employs a robust tech stack including PHP, HTML, JavaScript, CSS, and MySQL. PHP ensures dynamic data processing, while HTML and CSS contribute to the user-friendly interface. JavaScript enhances interactivity and a smooth user experience. MySQL acts as the backend database, ensuring secure data storage and retrieval.
- Programming Languages: PHP, HTML, JavaScript, CSS
- Frameworks/Libraries: Vanilla
- Databases: MySQL
- Other Tools: Future - Docker

## Setup and Installation

Requirements

Download and Install any local web server such as XAMPP/WAMP.
Download the provided source code zip file. (download button is located below.
Installation/Setup

1.Open your XAMPP/WAMP's Control Panel and start the Apache and MySQL.

2.Extract the downloaded source code zip file.

3.If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory. And If you are using WAMP, paste it into the "www" directory.

4.Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin

5.Create a new database naming bijapurpolice.

6.Import the provided SQL file. The file is known as ghpolice.sql located inside the DB File folder.

7.Browse the Police Crime Record Management System System in a browser. i.e. (http://localhost/bijapurpolice)  - rename to - http://localhost/se2024-de-leon-totanes.

Account Type and Password 

Admin

Account = 100 - Pass = djain123

Account =101 - Pass = agarwal123

NCO

Account =113 - Pass = ajay123

Account =114 - Pass = usmani123

Account =117 - Pass = bijapur123

CID

Account =115 - Pass = sukali123

Account =116 - Pass = attar123

Account =110 - Pass = shaikh123


## Usage Instructions

Open your XAMPP/WAMP's Control Panel and start the Apache and MySQL. If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory. And If you are using WAMP, paste it into the "www" directory.Browse the PHPMyAdmin in a browser Create a new database naming bijapurpolice.Import the provided SQL file. The file is known as ghpolice.sql located inside the DB File folder.Browse the Police Crime Record Management System System in a browser. i.e. http://localhost/Crime_Record_Managment_System-main.


## Project Structure
Project Directory:
```bash
.
.
└── Crime_Record_Managment_System-main/
    ├── \.git
    ├── \admin
    ├── \assets
    ├── \cid
    ├── \ckeditor
    ├── \class
    ├── \css
    ├── \database
    ├── \DB file/
    │   └── Bijapurpolice.sql
    ├── \interface
    ├── \js
    ├── \officer  
    ├── dbconnect.php
    ├── header.php
    ├── index.php
    ├── login.php
    ├── logincheck.php
    ├── menubar.php
    ├── readme.md
    ├── savecidstatement.php
    ├── scripts.php
    └── session.php
```

## Contributors

- **John Loinel R. De Leon**: Lead Developer, Backend Developer
- **Carla Totanes**: Frontend Developer, UI/UX Designer
- **Gerald Villaran**: Project Manager, Tester

## Project Timeline

- **Week 1-2**: Research and project planning.

    - Feature to Implement: Dockerize Project
    - Completion Date: 27/10/2024
      
- **Week 3-5**: Design and setup.
- **Week 6-10**: Implementation.
- **Week 11-12**: Testing and debugging.
- **Week 13-14**: Final presentation and documentation.

## Changelog

### [Version 1.0.0] - 2024-09-07
- Initial release of the project.

### [Version 1.1.0] - 2024-09-14
- Improved user interface for -
- Fixed bugs related to -
- Updated project documentation with setup instructions.

### [Version 1.2.0] - 2024-09-21
- Added new functionality for -
- Refactored codebase for better performance.



## Acknowledgments

Acknowledge any resources, mentors, or external tools that helped in completing the project.

This project was built from [Crime_Record_Managment_System-main](https://github.com/ddarrsh/Crime_Record_Managment_System), created by [ddarsh].
You can view the original repository (https://github.com/ddarrsh/Crime_Record_Managment_System).

## License

GNU General Public License version 2.0.
"# se2024-de-leon-totanes" 
