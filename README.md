# EXPERIMENT--01-ALP-FOR-8086
    Name: Surya Prakash B
    Roll no: 212224230281 
    Date of experiment: 24 - 04 - 2026





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
 
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

8.	Click on emulate to start emulation 


![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

9.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 


![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

````markdown
```assembly
MOV AX,1234H
MOV BX,3323H
ADD AX,BX
HLT
````

**Output**
![ADD](https://github.com/user-attachments/assets/982b0974-d021-4cbb-8b0f-c45251f1bfe6)

---

## Subtraction of 16-bit ALP

```assembly
MOV AX,1234H
MOV BX,3323H
SUB AX,BX
HLT
```

**Output**
![SUB](https://github.com/user-attachments/assets/8d8f33e7-6b2f-4485-b146-dbd7d3b3751b)

---

## Multiplication of ALP

```assembly
ORG 100H
MOV AX,1234H
MOV BX,3323H
MUL BX
HLT
RET
```

**Output**
![MUL](https://github.com/user-attachments/assets/1d8ce7a4-7144-4adc-8c85-38d025924149)

---

## Division of ALP

```assembly
MOV AX,1234H
MOV BX,3323H
DIV BX
HLT
```

**Output**
![DIV](https://github.com/user-attachments/assets/3143db33-b072-4a3e-8916-19ef194a1040)

---

## AND of 16-bit numbers ALP

```assembly
MOV AX,1234H
MOV BX,3323H
AND AX,BX
HLT
```

**Output**
![AND](https://github.com/user-attachments/assets/2c4e3e5b-099b-49a3-9fb0-13cf0544e9b9)

---

## OR of 16-bit numbers ALP

```assembly
MOV AX,1234H
MOV BX,3323H
OR AX,BX
HLT
```

**Output**
![OR](https://github.com/user-attachments/assets/711d28e5-f812-4b7d-83d5-74b0ee9d2d97)

---

## NOT of 16-bit number ALP

```assembly
MOV AX,1234H
NOT AX
HLT
```

**Output**
![NOT](https://github.com/user-attachments/assets/0d2e655a-375e-435e-8f23-f9c6bfeecd2d)

---

## XOR of 16-bit numbers ALP

```assembly
MOV AX,1234H
MOV BX,3323H
XOR AX,BX
HLT
```

**Output**
![XOR](https://github.com/user-attachments/assets/ad347c8a-b549-4f8f-a811-ea3e5e952d53)

```
```

## Result :
 

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
