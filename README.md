# Programming assignment 1

## Introduction
This is the solver program which is a n x m grid with more outside number. Each cell will contain a number between 1 and 9. The aim of a puzzle is to not have a number colored differently, such that
- The number of each column above is the same as the sum of the numbers in the black squares of the column.
- The number of each rows right is the same as the sum of the numbers in the white qwuares of the column.
- No information on the coloring is given, initially. 

## Inputs
Input is consist of numbers (between 1 and 9), and outside numbers. You should seperate these numbers into two colors. 
1:Black
2:White

### for example) 
```
20 23 30 29 34 6 9 21 19
8 2 1 8 1 3 5 7 6 18
9 1 4 2 5 6 3 1 7 28
3 5 1 4 9 1 3 9 1 8
8 6 6 3 5 1 1 4 1 4
8 6 6 2 6 8 3 3 9 31
8 7 8 8 4 5 2 1 1 18
4 8 3 5 5 2 1 2 8 24
1 2 8 8 8 3 7 2 7 22
8 3 9 5 9 2 1 4 9 35
```
## Outputs
Output is consist of numbers (between 1 and 9).
1:Black
0:White

### for example)
```
1 1 0 1 0 0 1 0 0
0 1 1 0 1 0 0 0 0
1 1 1 0 1 0 0 1 1
1 1 1 1 1 1 1 0 1
0 0 0 1 1 0 0 1 1
0 1 1 1 0 0 1 1 0
0 0 1 0 0 0 1 1 1
1 1 1 1 0 1 0 1 0
0 0 0 0 1 1 0 1 0
```
If there is no solution
```
No solution
```
## Build
First, download the zip file and make a executable file type.
```
gcc Q.c
make
```
Second, execute. Then, it will be printed with a message "Enter file name!!"
You should put the name of the input file.
```
Enter file name!! input.txt
```
Finally, you can see the results of the program.
