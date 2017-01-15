# Introduction


## Sequential Computer

Inside a computer, all information is encoded by means of integer, fixed length, numbers. To transfer information between the outside world and the computer translating devices, such as keyboards, displays, printers, temperature sensors, accelerometers etc. are required. We call them input or output interfaces. Often information can not be processed immediately after having been introduced in the computer. For instance, if one wants to know if the temperature is climbing, the actual value obtained from the temperature sensor needs to be compared with the previous value obtained from the same sensor. Therefor the computer has a data memory, where numbers can be stored as long as needed. These numbers can eventually be fetched from that memory, combined by an arithmetic calculator and the result stored also in the data memory. The different actions performed by the parts of the computer are initiated by a control unit that sends, at appropriate moments, electrical signals to these different parts as required for the specified task. This is called “execution of an instruction”. Instructions are encoded by means of integer numbers, stored in the program memory. The control unit fetches, one by one these instructions and executes them sequentially. The list of instructions to be executed is loaded into the program memory through an input interface, called here “program interface”.

### Input Interface

### Data Memory

- data can be stored 

### Arithmetic Unit

- calculate

### Control Unit

- the different actions performed are initialized by CU 

### Program Memory

### Program Interface

### Output Interface

### Instructions

- Instructions stored in the program memory, the control units fetches and execute them one by one sequentially 

## Memories

### each unit can contain one, fixed length, integer number and is identified by a number called address

## Instructions Format

Conceptually, a data handling (arithmetic) instruction is composed of 5 independent items:  
The nature of the operation that needs to be performed  
The addresses in data memory of the two operands that need to be combined by an arithmetic operation  
The address in data memory where the result of the operation needs to be stored  
The address in program memory where the next instruction will be fetched.  
If only data handling instructions existed, the sequence of executed instructions would be fixed in advance and could not be influenced by the value of some data items. Therefor a second variety of instruction, the control instructions, is required. In a control instruction the value of two data items are compared and the address of the next instruction to be fetched depends on the result of the comparison.

### the nature of operation that needs to be performed

### the address in data memory of two operands that need to bee combined by arithmetic operation

### the address in data memory where results stored

### next instruction fetched

- 

## Examples : the locked door

## computer

### Von Neumann Computer

### Harvard Architecture

## Memory

### Central memory, expensive part of storing the data and programs that are being used at that moment

### Peripheral memories 

- solid state disk

- magnetic disks

- flash memory sticks

- CDs / DVDs

### Archival stores, slow access but huge storage capacity and high reliability, based on magnetic tape cassettes

## Assembler

### source code->Object Code

### Assembling and Executing

- Loading the Assembler

- Assembling the language

- Loading the user’s program

- executing the user’s program

### Machine Vs Assembly Language

- Source code Format

- pseudo instruction

- forward references

### Assemblers

- 1 pass

	- fast but requires lot of memory space

- 2 pass

	- symbol table generation

	- object code generation

	- small but slow, reading twice source code, using intermediate code

### Variable Length Instructions

### Linker

### Lexical Analyzer

### Syntax Analyzer


# 


## if only the data handling instruction existed, the sequence of executed instruction would be fixed in advance and could not be influenced by the value of some data items

## the control instruction, two data items are compared and the address of the next instruction to be fetched depends on the result of comparison


# 


## two memories, one for data and another for instructions

## for vast majority of computers, designed and manufactured for a specific application


# 


## when we do not the application, optimizing separately word length and memory size for each two memory is meaningless

## combine program memories and data memories into one.


# 


## SC secret code

## kFL keyboard flag

## KDA keyboard data

## A numerical value preceded by the # sign means that the instruction will interpret that value as an operand rather than as the address of an operand.

## 

