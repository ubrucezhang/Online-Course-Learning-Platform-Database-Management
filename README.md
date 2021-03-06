# Project8_TrainlyIO


This project is intended for potential investors in the Trainly.io App Store, as well as for those interested in the database development process of a technology startup company. The code is compatible with Java and the system currently runs in the command line.

---
## Video

A link to a setup/installation video to help you get Trainly up and running:  
https://youtu.be/q9cBAFkdLU4

A link to a "demo" video showing input/output examples and the functionality of Trainly:  
https://youtu.be/sbfrm-AMeQQ

## Functionalities

Trainly.io aims to be the best source for higher education instruction and course management on the web. As development of Trainly.io continues, our goal is to structure the Trainly.io App Store as a collaborative and interactive hub for universities and their faculty, empowering organizations to work with their teaching staff to provide students with a centralized resource for all their online educational needs.

Faculty will be able to list courses available for registration, release course materials, and track student progress and competencies. Using faculty email addresses, faculty will also be able to search for their own courses, those being taught by their colleagues, and view enrollment statistics for each course. 

Students will be able to register for courses, track the completion of course materials, and post questions about course materials, either publicly to their class, or privately to course faculty.  Students can also view their course and account histories, allowing them to keep track of their tuition costs, completed and ongoing courses, and courses they are interested in taking.

The creation of Trainly.io is a response to the stated needs of students and universities for more functional, elegant and flexible educational software than is currently available. 

Trainly.io utilizes a MySQL-based Relational Database Management System (RDBMS).  This decision was made because of the flexibility of MySQL to interface with Web applications and to more readily integrate into existing systems.








---

## System Build

1. Download ```trainly.zip``` file, decompress it, and save it into a certain folder (eg. Downloads)

2. Open the terminal, and navigate to the directory where you saved the file by typing ``cd Downloads ``, then press enter.

3. Type ``cd trainly ``, then press enter.

4. Type ``ls``(small character 'L'), enter, to show the contents of your folder and verify that ``trainly           trainly.jar `` is listed.

5. Type ``java -jar trainly.jar``, then press enter.

6. You should now see the main menu, welcome to Trainly.


## Run the Main Menu

Once in the main menu you will have a set of options to choose from.

**1. Enter "1"** 
      
You are now in the Student Menu, and you are asked to enter your Student ID.
   
The student Id is supposed in the range of 241-340 based on the data we generated.For example, your student Id is 251, and you enter it.

You wil see a set of options in the Student Menu.

(1）Enter 1 if you want to know what courses you are interested in or have paid for.

   You will see the information about the courses you have completed, are enrolling and are interested in, including the course Id, name, primary topic, secondary topic and course rating.
      
   
(2) Enter 2 if you want to search the courses within a keyword.
      
   You will be asked to enter the keyword you want to search.
   
       For example, "java" is what you are interested in. Then just type "java".
    
       You will see all the courses has the keyword "java", including the course name, instructor offering the course, the</br> course rating and total number of course materials.
    
      If there is no course with the keyword you enter, it will show “Search returned empty” and return to the student  menu.

(3) Enter 3 if you want to enroll a course. 
      
      You will be asked to enter the course Id you want to enroll.
     
   
            For example, you would like to join "JavaScript: Understanding the Weird Parts" according to what you have just search, enter 3 (the course Id of the course). Then you will be asked to enter your payment code, entering date and time. You are supposed to write in the format it asks, or it will show Error.
    
      If you enter the course you have enrolled, it will show "You have enrolled in this course”. 
   
      The course Id you are supposed to enter is in the range of 1-27 based on the data we generated.

(4) Enter 4 if you want to take a look at the course materials of a certain course you are currently enrolling. 
      
      You will be asked to enter the course Id. It should be course you have enrolled according to the result 1.
    
      You will see the information of the all course materials related to this course, including course Id, course name, and material type as well as the description.
    
      If you enter the course Id you haven't enrolled or have finished, it turns out that ‘You are not enrolled in this course”.
    
(5) Enter 5 if you have just finished the a course material and want to record it. 
     
     You will be asked to enter the course Id, then the date and time.Then you will be asked to enter the finish date and time. You are supposed to write in the format it asks, or it will show Error.
   
     If you enter the course Id you have finished, it will show ‘You have finish all materials”.
   
     If you enter the course Id you haven’t enrolled, it will show ‘You are not enrolled in this course”.
 
(6) Enter 6 if you want to get the information about the course material of the most popular course among the courses you are interested in.
      
      You will be asked to enter the keyword of what you like, then it will show the course name, course id, course materail type and description.
    
(7) Enter 7 if you want to view the information about all the courses provided.
      
      You will see the course Id, name, instructor, primary topic, the number of students who enroll in the course, and the number of students who are interested in the course. It is shown in the order of the number of students who enroll in the course.
    
(8) Enter 8 if want to know your payment information. 
      
      It will show the payment information about the courses you have enrolled, including the course name, instructor, payment date, completion date, the fee and the payment code. Then it sums the total money you have spent.
      
    
(9) Enter 9 if you just want to see the certifications of the completed courses.
      
      You will see the certifications of all the completed courses, listing the course name, instructor, date and time of completion.
      
   
(10) Enter p if you want to return to the Main Menu.
      
(11) Enter q if you want to quit the program.
      


**2. Enter "2"**

You are now in the Faculty Menu, and you are asked to enter your Faculty ID.
      
The student Id is supposed in the range of 21-40 based on the data we generated.For example, your faculty Id is 22, and you enter it.
   
You wil see a set of options in the Faculty Menu.
   
(1) Enter 1 if you want to see the questions raised by students enrolling the courses you instruct.
      
      You will see all the questions related to the course you instruct, including the related topic, course name, question title and content, whether it is answered, person who asked it and how many students like it.
    
(2) Enter 2 if you want to get the information about the course instructed by a certain faculty (as well as you).
      
      You are asked to enter the faculty email, then it will show the course information of the faculty with this email, including the course name and how many student enroll the course. 
   
      If the email address you enter belong to no faculty, it will show "The email doesn’t belong to any faculty".
   
(3) Enter 3 if you want to see the information about all the faculty.
      
      You will see the information about every faculty, including his name, number of courses provided by him, the course revenue and which administrator admits him.
   
(4) Enter p if you want to return to the Main Menu.
      
(5) Enter q if you want to quit the program.
      


**3. Enter "3"**

 You are now in the Administrator Menu, and you are asked to enter your Administrator Id.
    
 The student Id is supposed in the range of 1-10 based on the data we generated.For example, your faculty Id is 2, and you enter it.
    
 You wil see a set of options in the Administrator Menu.
    
(1) Enter 1 if you want to authenticate a faculty.
      
      You will be asked to enter the faculty Id. Then you will be asked to enter the finish date and time. You are supposed to write in the format it asks, or it will show Error. 
   
      If the faculty has been authenticated, it will show “This faculty has been verified".
   
(2) Enter 2 if you want to authenticate a new administrator.
      
      You will be asked to enter the administrator Id. Then you will be asked to enter the finish date and time. You are supposed to write in the format it asks, or it will show Error. 
   
      If the administrator has been authenticated, it will show “This administrator has been verified".
   
(3) Enter 3 if you want to see the information about all the faculty.
      
      You will see the information about every faculty, including his name, number of courses provided by him, the course revenue and which administrator admits him.
   
(4) Enter 4 if you want to see the information about a certain student.
      
      You will be asked to enter the student Id. You will see the payment information about the course the student of this Id has enrolled, including the course name, professor, payment date, completion date, the fee and the payment code. Then it sums the total money the student has spent.

      If the Id doesn't exist, it will show “Student Id is not valid.”

(5) Enter p if you want to return to the Main Menu.
      
(6) Enter q if you want to quit the program.



**4. Enter "4"**

Enter 4 if you are new to the program and want to register as a user.
      
You are asked to enter your email, first name, last name, password, phone number, a link to your profile picture, address (including the street, city, country and postal code). Do it step by step as it requires.
      
Then you will see your user Id and student Id.
      


**5. Enter "q"**
      
Enter q if you want to quit the program.
