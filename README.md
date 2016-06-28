# computer_architecture_hw
This respository is for the assignment of Computer Architecture at the University of Tokyo. [Class HP] (http://www.mtl.t.u-tokyo.ac.jp/~sakai/hard/)

## Problem 1
Implement an assembler in Perl designed in class.

## Problem 2
Write a short code in assembly and assemle the program with the assembler created in problem 1.
Analyze the difference between assemble code and machine code.

Short code
```
add 2, 1, 1
```

Resulting machine language
```
000000_00001_00001_00010_00000000000_¥n
```
*Note that the order changes between two. 2 moves to the last as 00010 and 1, 1 moves forward.*
