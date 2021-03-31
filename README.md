## Course Registration system

For the course, CZ2002 - Object oriented design and principles, we had to build a course registration system modelled around the actual course registration system 
at the university. We had to ensure that our design was extensible and followed the SOLID principles. 

### Features

* Implemented basic student functionalities like checking for timetable clash, adding a course, dropping a course, swapping index etc.
* Implemented basic admin functionalities like adding new student, adding new course, changing course details.
* Dynamic database operations (database files are in .dat format)
* Password hashing and email notification API which sends emails to the student when he/she has registered for a course.
* Strong OTP based authentication when swapping index with a peer
* Fast execution as read and write only happen once

### Steps to run the code
1. Clone the repository
2. cd src 
3. Execute the LoginBoundary.java file

### Architecture
3-Layered architecture using boundary, controller and entity components forming the different layers respectively. Extensively used OOP concepts and 
SOLID design principles to ensure extensibility and loose coupling. javadoc has been prepared for further code and design analysis. 

### Contributors
1. Li Rui
2. Ye Xiyuan
3. Pandey Pratyush Kumar
4. Chaoshan
5. Xinyang (Victor)


