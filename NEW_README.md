# Terminology

- DBVM --> darkbite virtual machine
    - this is a hyperviser that operates at a lower level then the kernal and is able to access and modify the physical memory of the host sys
    - DBVM is "injected" into the vulnerable OS during <b>boot time initilization</b>.
- Hypervisor --> virtual machine monitor
    - allows multiple OS's to share a single hardware host
    - Manages hardware resources including CPU, memory, etc...
    - Since hypervisors have control over critical systems resources and operations, improper uses can brick yr pc
- File Extensions
    - .ddp (Dephi Diagram Portfolio) --> maybe UML Diagrams?
    - .lfm (Lazarus Form) --> layout information for lazurus application
    - .pas (Pascal File) --> Main Application Logic Code
    - .lpi (Lazarus Proj Info) --> Project Build Configs
    - 

# Current Analysis Focus
how cheat engine interacts with game --> look for modules that
- handle process memory manipulation
- hooking functions
- "sys" lvl operations

# Repo Breakdown

## Cheat Engine


## DBKKernal

### Overview
- Low Level Kernal Modules for performing high privilege tasks such as manipulating memory or accessing memory from protected spaces
- Can manipulate memory or access memory in protected spaces
- Eg. Grab a memory space from r6 



