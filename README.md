# CS5200

1. Requirements

Design a scheduling application for a driving school. 

Students of the driving school need to appoint online. More specifically, students need to find a suitable courses and have an appointment in the system. Each student can have zero or more reservations because a student can only register in the system and find a coach without an appointment. A course can be selected by zero or more students. Besides, each course has a certain coach and one coach can teach for many courses. To maitain the quality of the courses, it is best for a coach not to teach more than 5 courses.

The application also needs to store all information of students, courses and coaches. 

Firstly, students should sign with their first name, last name, gender. Moreover, each student could have one email address, and must have one phone number in the system, or the coaches cannot communicate with their students. Most importantly, the address is necessary for students because a coach needs to pick up students at a specific location. 

Secondly, the application needs to show coaches' first name, last name, phone number and the time they register on a coach. To help students make a better choice, it needs to show the ratings of coaches. Besides, location is also necessary for a student to find a suitable coach near home. 

Thirdly, the information of courses need to be shown. A course will have a name (maybe driving lesson: DLXXX). In addition, a car type name to help student find the specific type of car they would like to learn. Start time and duration tells the specific time to start the course and how long it will take. Capacity shows the maximum students in a certain course. Great with a short introduction. Finally, the coach of the course.





Nouns(Classes): students, courses, coach
Nouns(Attributes): 
Student: first name, last name, gender, email, phone, address.
Course: name, car type, start time, duration, capacity, introduction, coach
Coach: first name, last name, time to register on a coach, phone, ratings, location

Verbs(Assosiations): appoints


2.Conceptual Model *png

	./SQL_backup
	
3.Logical Model *png

	./SQL_backup
	
4.database *db *sql

	./SQL_backup
5.query *sql

	./SQL_backup
	
6.What is the project?

The project is to implement a web application for a driving school scheduling system allowing both managers and students to use it. Managers can create, read, update, and edit the courses' information from the manager page. Students can create an account, register for courses, and find information about them.

7.Team member contribution


Individual Contributions

Chang Guan implements: 
	UML class diagram
	Designing the page of managers, allowing managers to CRUD courses.
	CRUD operations on the courses' information
	CRUD appointments and implement adding students to a certain course.
	Query/ filter functions. Such as searching courses by name, sorting by start time.
	Implement the web application of manager's page, DB, and testing. Creating the database, and importing test data.

Tong Zhou implements:
	ERD and relational schema
	Designing the page of students, and students can create a new account, has a overview of courses and register in.
	CRUD operations on the students' information
	CRUD operations on the coaches' information
	Showing information of courses for students, including coaches' information and courses' information. 
	Implement the web application's student page, front-end, and back-end, redirections, debugging.
