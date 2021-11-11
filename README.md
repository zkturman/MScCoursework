# MSc Coursework
Includes overall MSc in Computer Science coursework for 20/21 school year
## Programming in C
This course focused on learning basic coding principles for the C language. All assignments required following an in-house style guide, which can be found [here][progInC styleGuide]. This course featured four main programming projects, and each featured a heavy emphasis on test-driven development.

[Forest Fires][progInC forestFires] features a basic simulation for the spreading of fires within a forest. The project involved taking a given two-dimensional array and transforming it based on given rules over a set number of generation. My final mark for this assignment was distinction.

[Happy Bookcases][progInC happyBookcases] involves a breadth-first search algorithm where a given two-demensional array of books must be sorted given certain parameters. The goal was to find the shortest number of moves to sort the bookcase. Because the algorithm is breadth-first, memory and performance management were important aspects. For the extension to this project, I attempted to improve the basic algorithm to choose the best likely solution, which allowed solving more complicated bookcases. My final mark for this assignment was a distinction.

[Poly Hashing][progInC polyHashing] focuses on creating a polymorphic hash table in C. The C programming language does not actually allow polymorphism, but this project explored a method in which you could attain a kind of polymorphic behaviour in C. The project involved two different methods for hashing. In the first, two hashing algorithms were used to add new elements to a table. A custom hashing algorithm was used for this base method. The second part of the project involved cuckoo hashing, which implements a second hash table to handle collisions when entries have the same key value.

[Turtle Parsing][progInC turtleParsing] parses and interprets a turtle-specific language. When the language is interpreted, a graphic display is created. This project used a recursive descent parser to make sure a given .ttl file contains correct syntax. When interpreting the file, SDL is used to render graphics. As an extension to the base program, I implemented the addition of colour interpretation, turtle 'jumping' (where a non-continuous line can be drawn), and random options for numbers and colours.

## Computer Architecture

[ARM exercise prepartion][arm practice]

## Intro to Computer Science

Add link to final essay

## Intro to Software Tools

Add summary of course

## Object Oriented Programming

[Noughts and Crosses][java oxo]

[Basic SQL Database Server][java db]

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
[java oxo]: https://github.com/zkturman/COMSM0086-OXO
[java db]: https://github.com/zkturman/COMSM0086-DB
[java stag]: https://github.com/zkturman/COMSM0086-STAG 
[segp sugarRush]: https://github.com/zkturman/SugarRush
