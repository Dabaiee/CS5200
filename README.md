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

2. Conceptual Model *png

3. Logical Model *png

4.database *db *sql

5. query *sql