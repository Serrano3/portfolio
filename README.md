# Personal Projects
### **1. Dynamic Wordle (C++)**

![](assets/img/WD0.PNG) 

#### **Project Overview**

- Contains three parts: main.cpp, setup.h, word.txt

- **main.cpp**
  -     Switch case is used to decide path and this file contains instruction for encyrption and decrypiton 
- **setup.h**
  -     The game is organized by Classes and regulated by the Constructor that performs necessary structuring logic and loops   
- **word.txt**
  -     contains the word that the player is trying to figure out and is encyrpted using the technique of repositioning

#### **Technical Details**

- Classes Using Inheritance and Public, Private and Protected
- Functions: Pass-by-Value and Pass-by-Reference with Return types
- Input and Output File-Stream
- Specialized Loops
- Switch Expression
- Header Files

#### **Main Menu**

![](assets/img/WD1.PNG) 

- **Reveal**
  -     This option obtains the encrypted word from word.txt and is deciphered followed by outputing to the player 
- **Change**
  -     This option takes the players word and enciphers it followed by over-writing the exisiting word in word.txt   
- **Launch**
  -     This option deciphers word and uses the class constructer to perform a series of task to start the game

#### **demonstration**

The header contains the instruction of game and the following is demonstration of the game.

![Demo Of Wordle](assets/img/WD4.PNG) 

After each attempt the list of letters at the top will removes the letters that are not in the word you are attempting figure out. 
The valid letters are highlight one of two colors to indicate the following. 

- **Green**
  -     That all of the letter have been placed in the correction position of the word you are attempting to figure out 
- **yellow**
  (Has two meanings)
  
  -     1.) A valid letter was correctly placed however not all of this letter have been found in the word
  -     2.) The letter is not in the correction position but it is in fact necessary to complete the word  

#### **Outline of Code**
![](assets/img/W1.PNG) 
![](assets/img/W2.PNG) 
![](assets/img/W3.PNG) 
![](assets/img/W4.PNG) 


### **2. 3D Torus Visualization (C++ & Assembly)**

![](assets/img/TorusG.PNG) 

#### **Project Overview**

- Contains three parts: torus.cpp, a10procs.asm, makefile

- **torus.cpp**
  -     This file includes everything necessary to initialize OpenGL and calls necessary functions from the assembly file
- **a10procs.asm**
  -     Read's the user's input from the command line to ensure all values are valid then calcuates the requested variables by the .cpp file
- **makefile**
  -     This makefile performs the neccesary steps to properly compile the .asm file to be able to run the program



#### **Technical Details**

- Linix enviroment with appropriate hardware or emulator designed to handle Assembly (x86_64)
- Functions: Pass-by-Value and Pass-by-Reference with Return types
- Understanding of Registers and handling differnt data types
- Understanding of CLA and converting string to integer
- Understand Standard Calling Conventions
- The installation of openGL

#### **Command Line Arguments from Terminal **

xx Need image here xx

#### **Result**
![Demo Of Wordle](assets/img/TorusP.PNG) 

#### **Outline of Code**
![](assets/img/T1.PNG) 
![](assets/img/t2.PNG) 
![](assets/img/T3.PNG) 
![](assets/img/T4.PNG) 
![](assets/img/T5.PNG) 
![](assets/img/T6.PNG) 
