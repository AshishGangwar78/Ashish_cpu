#_Ashish_cpu – A Simple CPU Simulator in C++

Ashish_cpu is a basic CPU simulation project written in C++. It mimics how a real CPU works internally — fetching, decoding, and executing instructions. This project helps visualize how instructions are processed inside a computer, making it a great tool for learning computer architecture from the ground up.



#_What This Project Does -

This simulator performs the following key tasks:

1.Fetches instructions from memory
2.Decodes them to understand what action is required
3.Executes them using a simulated Arithmetic Logic Unit (ALU)
4.Uses registers to temporarily store and manipulate data
5.Supports multiple instructions like LOAD, STORE, ADD, SUB, etc.


#_Problem It Solves-

Most students struggle to understand how CPUs actually work behind the scenes. This project breaks the CPU's internal process into clear, code-based components. It provides a hands-on way to learn about:

-The instruction cycle: fetch → decode → execute
-Register file usage
-Memory interactions
-Instruction-based control flow



##Project Structure

| File              | Description                                    |
|-------------------|------------------------------------------------|
| main.cpp        | Entry point of the CPU simulator               |
| cpu.h/cpu.cpp   | Core CPU logic — instruction cycle management  |
| memory.h/.cpp   | Handles memory read/write operations           |
| instruction.h/.cpp | Defines instruction format and operations   |
| register.h/.cpp | (If used) Emulates internal CPU registers      |



##Concepts Covered

-CPU architecture basics
-Instruction formats (like 'LOAD A, B')
-ALU operations (ADD, SUB, etc.)
-Program counter, memory access, and execution loop
-Simulated instruction set

