# OS-kernel-disk_simulator

## Prerequisites

- Linux operating system(Recommended), or if you could somehow compile C++ files on other OS and you know what are you are doing.

## Getting started 

- run **compile.sh** file to compile cpp files by the following commands:
```
chmod +x compile.sh

./compile.sh
```
- once compiled, run **main** file and give it number of processes as arguments by this command:

```
./main <num>
 ```
 #### Example
 ```
 ./main 2
 ```
 - you have to generate process files with the following format:
 ```
 processNUM.txt
 ```
 #### Example
 ```
 process0.txt
 
 process1.txt
 ```
 #### Format
 
 ```
 TIMESTEP OPERATION TEXT
 ```
 #### Example
 ```
 5 A HELLO WORLD
 7 D 0
 ```
 ## ARCHITECTURE SCHEME
 
 ![ARCHITECTURE SCHEME](/scheme.png)


