# BIT1123 Object-Oriented Programming
## Assignment 1 – Object-Oriented Programming Fundamentals in Java

---

## Student Information

| Information | Details |
|---|---|
| **Student Name** | Nurain Badrisyia Binti Mohd Ghazali |
| **Student ID** | 202307010013 |
| **Course** | BIT1123 Object-Oriented Programming 202605F0780 |

---
## Brief Course Description

BIT1123 Object-Oriented Programming focuses on developing programming skills using the Java programming language and understanding the fundamental concepts of Object-Oriented Programming (OOP).

Throughout the tutorials, I worked with Java classes, objects, constructors, methods, inheritance, encapsulation, abstraction, file handling, collections, and graphical user interfaces.

The assignment also helped me practise software development skills such as organising source code, using Git and GitHub for version control, maintaining a structured repository, and documenting my programming work.

---

## Repository Structure

The repository contains one folder for each tutorial period, together with the assignment report.

```
NURAIN-BADRISYIA_object-oriented-programming-tutorials/
│
├── README.md
├── myreport.pdf
│
├── week1/
│   ├── HelloWorld.java
│   └── StudentGrade.java
│
├── week2/
│   ├── Main.java
│   └── Student.java
│
├── week3-4/
│   ├── Main.java
│   ├── Person.java
│   ├── Student.java
│   └── Lecturer.java
│
├── week5/
│   ├── Main.java
│   ├── sTudent.java
│   └── documentation.txt
│
├── week6/
│   ├── Main.java
│   ├── Employee.java
│   └── Lecturer.java
│
├── week7/
│   ├── Main.java
│   └── Appliances.java
│
├── week8-9/
│   ├── Main.java
│   └── task.txt
│
└── week10/
    ├── Questions.java
    └── QuizBattleGUI.java
```
---
## Tutorial Summary (Week 1-10)

Week 1 – Getting Started with Codespaces via GitHub
Week 1 introduced the use of GitHub and GitHub Codespaces for Java programming. I created the repository and learned how to organise tutorial files inside folders. I also learned basic Git commands such as git status, git add, git commit and git push.
Main focus:
- GitHub repository setup
- GitHub Codespaces
- Java project organisation
- Basic Git commands
- Java source files

Week 2 – Coding in Java Programming Language
Week 2 focused on basic Java programming using classes and objects. I created a Student class containing attributes such as name, age and GPA. I also used a constructor to initialise the student information and methods to display information and perform actions.
Main concepts:
- Classes
- Objects
- Attributes
- Constructors
- Methods
- Object creation

Week 3–4 – Inheritance and Method Overriding
Week 3 and Week 4 introduced inheritance using a university people scenario. A Student and Lecturer were created as subclasses of the Person class.
The tutorial also introduced method overriding, where different classes provide their own implementation of the introduce() method.
Main concepts:
- Inheritance
- Parent and child classes
- extends
- super
- Method overriding
- Polymorphism

Week 5 – Encapsulation
Week 5 focused on encapsulation through a Student Information System. Student information such as student ID, name, and CGPA was protected using private variables.
Getters and setters were used to access and modify the private information.
Main concepts:
- Encapsulation
- private variables
- Getters
- Setters
- Data protection
- Controlled access to data

Week 6 – Employee and Lecturer
Week 6 continued the study of inheritance using an employee and lecturer scenario. A lecturer inherits common information from the Employee class while also having additional information such as subject and department.
Main concepts:
- Inheritance
- extends
- super()
- Protected attributes
- Reusing parent-class properties
- Adding child-class functionality

Week 7 – Smart Home Appliance Management System
Week 7 introduced abstraction using a smart home appliance scenario. An abstract Appliance class was used to provide common functions such as turning appliances on and off while allowing individual appliances to implement their own operation.
Main concepts:
- Abstraction
- Abstract classes
- Abstract methods
- Common behaviour
- Different implementations

Week 8–9 – To-Do List and File Handling
Week 8 and Week 9 focused on creating a simple task management application. The program allows users to enter three tasks and stores them using an ArrayList.
The program was then extended to save the tasks into a text file and read the saved tasks from the file.
Main concepts:
- ArrayList
- Loops
- User input
- File writing
- File reading
- BufferedWriter
- BufferedReader
- Exception handling

Week 10 – Programming Quiz Battle GUI
Week 10 introduced a simple graphical user interface using Java Swing. The Programming Quiz Battle application displays a programming question and provides two answer buttons.
The application checks the selected answer and displays whether the answer is correct or incorrect.
Main concepts:
- Java Swing
- GUI programming
- JFrame
- JButton
- JLabel
- Event handling
- ActionListener
- Object interaction

---

## Technologies Used
The following technologies and tools were used throughout the tutorials:
- Java: Main programming language
- Java Development Kit (JDK): Used to compile and run Java programs
- GitHub: Used for repository management and version control
- GitHub Codespaces: Used as the development environment for Java tutorials
- Git: Used to track and upload changes to the repository
- Java Swing: Used to develop the Week 10 graphical user interface
- ArrayList: Used to store multiple task items in Week 8–9
- Java File I/O: Used to save and load tasks from a text file

---
## How to Run the Projects
### 1 – Clone the Repository
Clone the repository using Git:
```bash
git clone YOUR-GITHUB-REPOSITORY-URL
```
Move into the repository:
```bash
cd YOUR-REPOSITORY-NAME
```

### 2 - Open the Required Tutorial Folder
For example, to run Week 2:
```bash
cd week2
```

### 3 – Compile the Java Files
For a tutorial containing multiple Java files:
```bash
javac *.java
```
For a single Java file:
```bash
javac Main.java
```

### 4 – Run the Program
For tutorials where Main is the main class:
```bash
java Main
```
For Week 10:
```bash
cd week10
javac *.java
java QuizBattleGUI
```
The Week 10 application will open as a Java Swing graphical interface.

Example: Running Week 8–9
```bash
cd week8-9
javac Main.java
java Main
```
The program allows the user to enter three tasks, displays them in the terminal, saves them to task.txt and then loads the saved tasks from the file.

---
## Reflection Summary
Completing the tutorials helped me develop a stronger understanding of Java and Object-Oriented Programming. 
At the beginning, I mainly focused on understanding the syntax and basic structure of Java programs. As the tutorials progressed, I became more familiar with 
how classes and objects work together. The inheritance tutorials helped me understand how a child class can reuse properties and methods from a parent class. 
The encapsulation tutorial showed me why data should be protected using private variables and accessed through getters and setters. 
I also learned that abstraction can be used to provide common functionality while hiding implementation details.

The later tutorials helped me apply Java concepts to more practical situations. The Week 8–9 task management program introduced me to storing information using 
an ArrayList and saving information into a file. Week 10 introduced Java Swing and showed me how Java can be used to create a simple graphical application. 
I also improved my ability to use Git and GitHub throughout the tutorials. 
Creating folders, committing changes and pushing my work helped me understand the importance of organising and maintaining programming projects properly.

Although some of the coding activities were challenging, especially when several concepts had to be used together, completing the tutorials helped me become 
more confident in analysing errors and understanding how the different parts of a Java program work together. 
Overall, this assignment gave me practical experience with Java programming and the fundamental concepts of Object-Oriented Programming. It also helped me understand that programming is not only about writing code, but also about organising, testing, debugging, documenting and maintaining the work properly.
