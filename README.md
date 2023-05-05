Download Link: https://assignmentchef.com/product/solved-cse240-homework-9-c-class-and-input-output
<br>
Introduction

The aim of this assignment is to make sure that you understand and are familiar with the concepts covered in the lectures and input/output. By the end of the assignment, you should have understood

<ul>

 <li>Class, data members and function members</li>

 <li>Classes and header files</li>

 <li>Memory management and garbage collection</li>

 <li>C++ input and output</li>

</ul>

<strong>Reading</strong>:​ Textbook Chapter 3, Sections 3.1, 3.2, and 3.3 on C++ examples, class definition and memory management.

<strong>Preparation</strong>:​ Complete the multiple choice questions in the textbook exercise section. The answer keys can be found in the course Web site. These exercises can help you prepare for your weekly quiz and the exam. You are encourage to read the other exercise questions and make sure you understand these questions in the textbook exercise section, which can help you better understand what materials are expected to understand after the lectures and homework on each chapter.

You are expected to do the majority of the assignment outside the class meetings. Should you need assistance, or have questions about the assignment, please contact the instructor or the TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board. However, <strong>do</strong>​<strong> not share your answers and code</strong> in the course discussion board.​

Programming Assignment

<ol>

 <li>You are given a partially completed project containing:</li>

</ol>

<ul>

 <li><u>header file:</u></li>

</ul>

book.h             (contains the class ‘Book’)

<ul>

 <li><u>C++ files:</u></li>

</ul>

book.cpp          (contains the class function definitions)

hw09q1.cpp     (contains the program to work on array of ‘Book’ objects)

In VS, create an empty C++ project. Then add the header file and CPP files, respectively, into your project as shown in the following screenshot:

If you use ASU General g++, then simply put the .h and .cpp files in one folder and compile with this command:

g++ book.cpp hw09q1.cpp -o <em>outputname</em>​

Your job is to follow the instructions given in the comments of the hw09q1.cpp and book.cpp files to complete the missing parts of the project so that the program executes properly. You should first complete book.cpp and then go on to hw09q1.cpp. NOTE: In the homework, list means an array (not a linked list).

This is a menu-driven program that uses following options:

<ol>

 <li>Add a new book to the list. The book details (book name, author name, publication year, number of copies) are given as function arguments. You should add the book to the list only if the book is not already present in the list and there is space in the array to add a new book.</li>

 <li>Display the book information of all books in the list. See expected output.</li>

 <li>Sort the book in the list by book name.</li>

 <li>Find the newest book in the list. You have to necessarily use the ‘Book’ pointer declared in the function and delete it before exiting the function.</li>

</ol>

You should start completing the program beginning from Q1. Question numbers are given on line 31 in hw09q1.cpp. ( Q1 – Q2 in book.cpp and Q3 – Q6 in hw09q1.cpp)


