# MSc Coursework
Includes overall MSc in Computer Science coursework for 20/21 school year. Most recent projects/courses are listed first.

## MSc Dissertation
### [UnderGrove Prototype (Playable)][dissertation undergrove]
  - Top-down adventure game
  - Developed using Unity and C#
  - Features custom procedure generation algorithm
    - Creates a two-dimensional dungeon
    - Dungeon rooms fit together logically, i.e. no rooms overlap geometrically
    - Entire map would resemble an actual blueprint
  - Features random generation of monsters, chests, and loot
  - Included educational features surrounding dark game design patterns
    - Relies on a second procedure generation aspect
    - Conditionally add adverts, loot chests
    - Change how long the game takes to complete
    - Convert all settings into shareable code to make game more social
  - Custom art, sound effects, and UI

## Software Engineering Group Project

### [SugarRush Group Project][segp sugarRush] - An Educational Game About Sugar
  - Quiz-based game to educate users on sugar consumption
  - Developed using the MEAN stack (MongoDB, Express, Angular, and Node)
  - Acted as project manager in an Agile environment
  - Creating and managed weekly sprints to help deliver MVP by end of term
  - Created services to maintain data between pages
  - Created end of game summary to review all player answers
  - Helped connect database to website

## Object Oriented Programming (Java)

The object-oriented programming course focused on implementing object-oriented concepts in Java. This course focused primarily on developing medium-sized projects and self-learning OOP principles. Over the period of the course, I completed three main projects.

### [Text-based Adventure Game Engine][java stag] - A Text Based Game Engine
  - Created a text-based game engine
  - Allowed users to create games using .dot and .json files
    - Locations were specificed using JSON format
    - Allowed player actions were specified using DOT format
  - Engine supported multiple players, where one player's actions affected the game world for everyone else's. 

### [Basic SQL Database Server][java db] 
  - Created a database server
  - Interpreted SQL-like language to act upon database
    - Required a basic parser
    - Used RegEx extensively to identify types of queries
    - Boolean and conditional expressions were parsed by converting to Reverse Polish Notation, allowing interpretation of complex logic with nested paretheses.
  - Utilised hash sets and dictionary data structures
  - Worked with file reading and writing
    - SQL Tables were represented using files: attributes in one and data in the other

### [Noughts and Crosses][java oxo] - AKA Tic Tac Toe
  - Create Noughts and Crosses game
  - Expandable board size, so the game isn't limited to a 3x3 grid
  - Dynamic win condition (number of noughts or crosses in a row) 
  - Applying solution to the backend of an existing frontend product
  - Focused on ArrayList data structure and searching for a satisfied win condition

## Intro to Software Tools

This course introduced an array of technologies and how they can be used in software development. The course was broken into four main modules. 

#### POSIX and Git
In the first module, we focused on POSIX and Git. We learned the basic Git controls and how to create a new Git repository. We also learnd how to use Git in a team environment and how to handle merge conflicts. When working with POSIX, we focused on some advanced C programming concepts, such as pipes and concurrent programming.

#### Relational Databases (SQL and SQL tools)
During the second module, we focused on relational databases through the use of Maria DB within an Alpine Linux environment. When learning about relational databases, we primarily focused on writing queries, but we also learned about ER diagrams and normal forms. After developing initial query-writing skills, we also looked at tools that combine the use of SQL within Java, such as JDBC and Hibernate.

#### Build Tools (Make and Maven)
In the third module for the course, we briefly explored the build tools make for C and Maven for Java. This module was mainly an introduction to these tools and briefly involved using them, but did not go into great depth. The most important thing I remember is that make seems like it can be really challenging to use for installing large programs.

#### Web Technology
In the final module of the course, we focused on web development skills. The course briefly explored how webpages and the internet work, along with a history of HTML and its relationship with CSS and JavaScript. As part of the module we worked on developing a simple webpage using HTML, CSS, and JavaScript. We then focused on how to implement different RESTful API requests, such as GET and POST. The module concluded with a brief introduction to React and re-implmenting our existing website using this framework.

The course website with further information can be found [here][softwareToolsSite].

## Programming in C
This course focused on learning basic coding principles for the C language. All assignments required following an in-house style guide, which can be found [here][progInC styleGuide]. This course featured four main programming projects, and each featured a heavy emphasis on test-driven development.

### [Turtle Parsing][progInC turtleParsing] 
Parses and interprets a turtle-specific language. When the language is interpreted, a graphic display is created. This project used a recursive descent parser to make sure a given .ttl file contains correct syntax. When interpreting the file, SDL is used to render graphics. As an extension to the base program, I implemented the addition of colour interpretation, turtle 'jumping' (where a non-continuous line can be drawn), and random options for numbers and colours.

[Add produced images and gif]

### [Poly Hashing][progInC polyHashing] 
Focuses on creating a polymorphic hash table in C. The C programming language does not actually allow polymorphism, but this project explored a method in which you could attain a kind of polymorphic behaviour in C. The project involved two different methods for hashing. In the first, two hashing algorithms were used to add new elements to a table. A custom hashing algorithm was used for this base method. The second part of the project involved cuckoo hashing, which implements a second hash table to handle collisions when entries have the same key value.

### [Happy Bookcases][progInC happyBookcases] 
Involves a breadth-first search algorithm where a given two-demensional array of books must be sorted given certain parameters. The goal was to find the shortest number of moves to sort the bookcase. Because the algorithm is breadth-first, memory and performance management were important aspects. For the extension to this project, I attempted to improve the basic algorithm to choose the best likely solution, which allowed solving more complicated bookcases. My final mark for this assignment was a distinction.

[![happyBookcasesDemo](https://img.youtube.com/vi/Tnrxt35YTrw/0.jpg)](https://www.youtube.com/watch?v=Tnrxt35YTrw)

### [Forest Fires][progInC forestFires] 
Features a basic simulation for the spreading of fires within a forest. The project involved taking a given two-dimensional array and transforming it based on given rules over a set number of generation. My final mark for this assignment was distinction.

[![forestFireDemo](https://img.youtube.com/vi/1O9cLKK-xTY/0.jpg)](https://www.youtube.com/watch?v=1O9cLKK-xTY)

## Computer Architecture

This course focused on computer architecture and featured two main units, and only exams were used for coursework. In the first unit, circuit logic was explored, which involved learning about different logic gates, memory, arithmetic, and finite state machines. To study circuits, the program Logisim was used. Towards the end of this unit, finite state machines were explored.

The second unit of the course involved primarily self-taught for ARM development and assembly language in general. The final exam for this course surrounded understanding of the basics of ARM development, but test preparation for similar types of development can be found in my [ARM exercise prepartion][arm practice] repository.

## Intro to Computer Science

This course provided an introduction to the different fields of computer science and dissertation writing. Throughout the course, a previous dissertation was used as the focus for all exercises. At the end of the term, each student was required to submit a paper focusing on this dissertation. In the paper, students needed to write an executive summary, provide feedback on strengths and weaknesses, review ethical considerations, and describe potential future work for the disseration.

[Add link to final essay]

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
[dissertation undergrove]: https://github.com/zkturman/UnderGrove
