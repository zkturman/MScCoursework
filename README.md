# MSc Coursework
Includes overall MSc in Computer Science coursework for 20/21 school year. Most recent projects/courses are listed first. I received a distinction for each course below.

## MSc Dissertation
### [UnderGrove Prototype (Playable)][dissertation undergrove] - [Link to Dissertation][dissertation paper]
  - Top-down adventure game
  - Developed using **Unity and C#**
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
  - Developed using the MEAN stack (MongoDB, Express, Angular, and Node), so plenty of **HTML, JavaScript, and CSS**
  - Acted as project manager in an Agile environment
  - Creating and managed weekly sprints to help deliver MVP by end of term
  - Created services to maintain data between pages
  - Created end of game summary to review all player answers
  - Helped connect database to website

## Object Oriented Programming (Java)

The object-oriented programming course focused on implementing object-oriented concepts in **Java**. This course focused primarily on developing medium-sized projects and self-learning OOP principles. Over the period of the course, I completed three main projects.

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

#### Git
  - **Git** commands
  - Creating and managing shared repositories
  - Handling merge conflicts. 
#### POSIX
  - Pipes in **C**
  - Concurrent programming in **C**

#### Relational Databases (SQL and SQL tools)
  - Use of **Maria DB** in **Alpine Linux** environment
  - Writing SQL queries
  - Creating and reviewing ER diagrams
  - Analysing databases for **normal forms**
  - Reviewing tools that access **SQL** databases through **Java**, such as **JDBC** and **Hibernate**.

#### Build Tools
  - Reviewed **Make** for **C**
  - Reviewed **Maven** for **Java**

#### Web Technology
  - Develop simple webpages using **HTML**, **CSS**, and **JavaScript**. 
  - Implement RESTful API requests, such as GET and POST
  - Introduced to **React**

The course website with further information can be found [here][softwareToolsSite].

## Programming in C
This course focused on learning basic coding principles for the C language. All assignments required following an in-house style guide, which can be found [here][progInC styleGuide]. This course featured four main programming projects, and each featured a heavy emphasis on test-driven development.

### [Turtle Parsing][progInC turtleParsing]
  - Parses and interprets a turtle-specific language in **C**
  - Utilises a recursive-descent parser
  - Language is interpreted to create graphic displays (see images below) using SDL to render graphics

#### Generated Images
<img src="https://github.com/zkturman/1201TurtleParsing/blob/main/GFX/cityscape.png" width="400px">
<img src="https://github.com/zkturman/1201TurtleParsing/blob/main/GFX/meander.png" width="400px">
<img src="https://github.com/zkturman/1201TurtleParsing/blob/main/GFX/umbrella.png" width="400px">
<img src="https://github.com/zkturman/1201TurtleParsing/blob/main/GFX/fractures.png" width="400px">
<img src="https://github.com/zkturman/1201TurtleParsing/blob/main/GFX/fadecirc.png" width="400px">

### [Poly Hashing][progInC polyHashing]
  - Creates polymorphic hash table in **C**
  - Explored different hashing algorithms for hashing new elements
  - Explored cuckoo hashing scheme to handle collisions when multiple elements have the same hashing value 

### [Happy Bookcases][progInC happyBookcases]
  - Finds a shortest solution for sorting an unsorted bookcase in **C**
  - Focuses on using a breadth-first search algorithm
  - Central focus on memory and performance
  - Required improving initial algorithms to get subsequent solutions

[![happyBookcasesDemo](https://img.youtube.com/vi/Tnrxt35YTrw/0.jpg)](https://www.youtube.com/watch?v=Tnrxt35YTrw)

### [Forest Fires][progInC forestFires] 
  - Simulate forest fires in **C**
  - Required navigating and mutating a two-dimensional array
  - Similar to John Conway's Game of Life

[![forestFireDemo](https://img.youtube.com/vi/wL8mZYYNrNg/0.jpg)](https://www.youtube.com/watch?v=wL8mZYYNrNg)

## Computer Architecture

#### Circuit Logic 
  - Learned about different logic gates
  - Studied NAND-gate-based models for memory, arithmetic, and finite state machines
  - Utilised the Logisim program for circuit simulations
  - Created and examined finite state machine logic
  - Focused on Boolean algebra and logic expressions

#### ARM Assembly
  - Required self-teaching **ARM assembly language**
    - Learned basic syntax of language
    - Programs can be found [in my ARM exercise][arm practice] repository
  - Required writing programs in **ARM**
  - Required learning about different physical components of computers

## Intro to Computer Science

  - General introduction to the different fields of computer science
  - Learned techniques for dissertation writing
  - Reviewed and critiqued previous dissertations
  - Presented information regarding dissertation to fellow classmates
  - Learned skills for writing executive summaries
  - Reviewed software ethics and applied principals to existing projects

### [Link to Final Paper](Turman_bm20715_Final_Paper.pdf)

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
[dissertation paper]: Under_Grove__MSc_Dissertation.pdf
[intro paper]: Turman_bm20715_Final_Paper.pdf
