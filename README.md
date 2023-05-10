# **DATA STRUCTURE & ALGORITHM**

# Mini Project Documentation: <br>FINAL YEAR PROJECT MANAGEMENT SYSTEM

Lecturer: Ts Dr Johanna binti Ahmad


Members: 
1. Felicia Chin Hui Fen (A20EC0037) - Leader
2. Gui Yu Xuan (A20EC0039）
3. Saidah Binti Saiful Bahari (A20EC0141)


## **Overview:**

<p align=justify> The Final Year Project System is a system in which users check the final
year projects of the students. The Final Year Project System stores the information
of the students and supervisor in a text file to facilitate the final year project
process. The design is simple because it provides a clear interface for users to
understand. The Final Year Project System consists of two users, which are
supervisor and students. Students use the Final Year Project System to check the
marks of the project. The supervisor uses the Final Year Project System to enter
marks and comments for the students’ final year projects. The system will list
down the students’ information such as name, id, course, section and project name
to the supervisor for them to key in the marks and comment. For students, the
system will list down the overall information of all students such as students’
name, id, course, section, project name, marks, grade and comment for the student
to view.</p>



## **Funtions:**
1. Insert students' marks
2. Delete students' marks
3. Search  students' information
4. Display students' information




## **Concept Applied:**

<p align=justify> The data structure applied in this system is the linked list and queue. We
perform the linked list concept in the queue. For the linked list, we have
implemented two linked lists to link two types of student information. Firstly, we
used student class pointers, “frontPtr” and “backPtr” in the class queue to link all
the student information. Other than that, we used “head” and “tail” pointers to
link the students’ login information (students’ name, id and password) in the class
queue. In order to link to the next pointer, we assigned a pointer named “next” in
the student class. Almost all the functions in the system have applied the linked
list concept. For example, the insertQueue function had used the linked list
concept to store the students’ information in the queue with the idea of
First-In-First-Out.</p>
<p>For the queue, we have used the insertQueue function to store all student
information and display function to display all the information of the student. The
First-In-First-Out concept is applied, where the first student information will be
stored in the queue and it will be displayed first on the screen. </p>
