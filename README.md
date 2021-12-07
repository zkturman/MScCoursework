# MSc Coursework
Includes overall MSc in Computer Science coursework for 20/21 school year.

## Programming in C
This course focused on learning basic coding principles for the C language. All assignments required following an in-house style guide, which can be found [here][progInC styleGuide]. This course featured four main programming projects, and each featured a heavy emphasis on test-driven development.

[Forest Fires][progInC forestFires] features a basic simulation for the spreading of fires within a forest. The project involved taking a given two-dimensional array and transforming it based on given rules over a set number of generation. My final mark for this assignment was distinction.

[Add picture or gif]

[Happy Bookcases][progInC happyBookcases] involves a breadth-first search algorithm where a given two-demensional array of books must be sorted given certain parameters. The goal was to find the shortest number of moves to sort the bookcase. Because the algorithm is breadth-first, memory and performance management were important aspects. For the extension to this project, I attempted to improve the basic algorithm to choose the best likely solution, which allowed solving more complicated bookcases. My final mark for this assignment was a distinction.

[Add picture or gif]

[Poly Hashing][progInC polyHashing] focuses on creating a polymorphic hash table in C. The C programming language does not actually allow polymorphism, but this project explored a method in which you could attain a kind of polymorphic behaviour in C. The project involved two different methods for hashing. In the first, two hashing algorithms were used to add new elements to a table. A custom hashing algorithm was used for this base method. The second part of the project involved cuckoo hashing, which implements a second hash table to handle collisions when entries have the same key value.

[Turtle Parsing][progInC turtleParsing] parses and interprets a turtle-specific language. When the language is interpreted, a graphic display is created. This project used a recursive descent parser to make sure a given .ttl file contains correct syntax. When interpreting the file, SDL is used to render graphics. As an extension to the base program, I implemented the addition of colour interpretation, turtle 'jumping' (where a non-continuous line can be drawn), and random options for numbers and colours.

[Add produced images and gif]

## Computer Architecture

This course focused on computer architecture and featured two main units, and only exams were used for coursework. In the first unit, circuit logic was explored, which involved learning about different logic gates, memory, arithmetic, and finite state machines. To study circuits, the program Logisim was used. Towards the end of this unit, finite state machines were explored.

The second unit of the course involved primarily self-taught for ARM development and assembly language in general. The final exam for this course surrounded understanding of the basics of ARM development, but test preparation for similar types of development can be found in my [ARM exercise prepartion][arm practice] repository.

## Intro to Computer Science

This course provided an introduction to the different fields of computer science and dissertation writing. Throughout the course, a previous dissertation was used as the focus for all exercises. At the end of the term, each student was required to submit a paper focusing on this dissertation. In the paper, students needed to write an executive summary, provide feedback on strengths and weaknesses, review ethical considerations, and describe potential future work for the disseration.

[Add link to final essay]

## Intro to Software Tools

This course introduced an array of technologies and how they can be used in software development. The course was broken into four main modules. 

In the first module, we focused on POSIX and Git. We learned the basic Git controls and how to create a new Git repository. We also learnd how to use Git in a team environment and how to handle merge conflicts. When working with POSIX, we focused on some advanced C programming concepts, such as pipes and concurrent programming.

During the second module, we focused on relational databases through the use of Maria DB within an Alpine Linux environment. When learning about relational databases, we primarily focused on writing queries, but we also learned about ER diagrams and normal forms. After developing initial query-writing skills, we also looked at tools that combine the use of SQL within Java, such as JDBC and Hibernate.

In the third module for the course, we briefly explored the build tools make for C and Maven for Java. This module was mainly an introduction to these tools and briefly involved using them, but did not go into great depth. The most important thing I remember is that make seems like it can be really challenging to use for installing large programs.

In the final module of the course, we focused on web development skills. The course briefly explored how webpages and the internet work, along with a history of HTML and its relationship with CSS and JavaScript. As part of the module we worked on developing a simple webpage using HTML, CSS, and JavaScript. We then focused on how to implement different RESTful API requests, such as GET and POST. The module concluded with a brief introduction to React and re-implmenting our existing website using this framework.

The coursewebsite with further information can be found [here][softwareToolsSite].

## Object Oriented Programming

The object-oriented programming course focused on implementing object-oriented concepts in Java. This course focused primarily on developing medium-sized projects and self-learning OOP principles. Over the period of the course, I completed three main projects.

In [Noughts and Crosses][java oxo], students were tasked with implementing features for a type of Noughts and Crosses game with a twist, the board and win conditions were dynamic. The goal of the project was to implement a data model that could handle such specifications, and as a result focused primarily on the use of ArrayLists. The assignment also required checking for win conditions in the board after each players move.

[Basic SQL Database Server][java db] focused on creating a database server and interpreting a SQL-like language to act upon it. To create a representation of a database and tables, directories and text files were used. Tables were represented using a combination of files. In the first, the attributes for a table were assigned. The other stored the table's data. For the interpretation of SQL queries, a basic parser was created, but without a specific algorithm in mind. However, regex was used pretty extensively to help determine the type of query. To handle Boolean expressions, reverse Polish notation was used. This methodology allowed interpretation of complex logic, and was used for both WHERE and JOIN clauses. 

[Text-based Adventure Game Engine][java stag]

## Software Engineering Group Project

[SugarRush Group Project][segp sugarRush]

## MSc Dissertation

Add link to game prototype and copy of dissertation.

[progInC styleGuide]: https://github.com/csnwc/Exercises-In-C/blob/main/exercisesInC.pdf
[progInC forestFires]: https://github.com/zkturman/1201ForestFire
[progInC happyBookcases]: https://github.com/zkturman/1201HappyBookcases
[progInC polyHashing]: https://github.com/zkturman/1201PolyHashing
[progInC turtleParsing]: https://github.com/zkturman/1201TurtleParsing
[arm practice]: https://github.com/zkturman/ARM-Playground
[softwareToolsSite]: https://cs-uob.github.io/COMSM0085/
[java oxo]: https://github.com/zkturman/COMSM0086-OXO
[java db]: https://github.com/zkturman/COMSM0086-DB
[java stag]: https://github.com/zkturman/COMSM0086-STAG 
[segp sugarRush]: https://github.com/zkturman/SugarRush
