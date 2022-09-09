# EXPERIMENT--01-ALP-FOR-8086

Name :EASWAR.J

Roll no : 212221230024

Date of experiment : 09/09/22


## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations

## Components required: 
8086  emulator 

## Theory :

Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.



 ## Running the Emulator :
 
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory

2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color .

3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 

5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 

7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,

8.	![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)


9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations
```
name "ADDITION"
org 100h
MOV AH,05H;
MOV BH,02H;
ADD AH,BH;
MOV CH,AH;
MOV AH,0H; 
MOV BH,0H;
HLT;
```
## Addition  of 8 bit ALP 
```
name "ADDITION"
org 100h
MOV AH,05H;
MOV BH,02H;
ADD AH,BH;
MOV CH,AH;
MOV AH,0H; 
MOV BH,0H;
HLT;
```

## Output  
 ![MC_ADD](https://user-images.githubusercontent.com/94154683/189397411-0b3efc02-33f3-465a-b22d-0b88b338a1ec.jpeg)

## Subtraction   of 8 bit numbers  ALP 
```
name "SUBTRACTION"
org 700h
MOV AH,7H;
MOV BH,5H;
SUB AH,BH;
MOV CH,AH;
MOV AH,0H;
MOV BH,0h;
HLT;
```

## Output  
![MC_SUB](https://user-images.githubusercontent.com/94154683/189397477-f7cd0fe4-ec14-4110-805e-1fbf1277cef2.jpeg)

## Multiplication alp 
```
name "MULTIPLICATION"
org 700h
MOV AX,5H;
MOV BX,4H;
MUL BX;
MOV CX,AX;
MOV AX,0H;
MOV BX,0h;
HLT;
```
## Output  
![MC_MULT](https://user-images.githubusercontent.com/94154683/189397611-6ff347a9-ac2c-4ac9-9253-d84c39ba95b0.jpeg)


## Division alp 
```
name "DIVISION"
org 700h
MOV AX,9H;
MOV BX,3H;
DIV BX;
MOV CX,AX;
MOV AX,0H;
MOV BX,0h;
HLT;
```
## Output  
![MC_DIV](https://user-images.githubusercontent.com/94154683/189397675-efee94c7-04d4-428f-8f1b-4a331e01ff2e.jpeg)


## Result :
Thus a program on ALP for the fundamental arithmetic and logical operations is done successful.
