# BankerAlgorithm

## Information
* Name: Khushi Patel
* Assignment: Banker's Algorithm
* Date: 21th april 2022

## What to do?
* To see if the system is safe or not
* You need to read data from a file

## Solution
* There are three 2-D arrays from reading file 
* There is a flag to keep track of the processes
* This will also check for avoiding deadlock
* At the end, it will say if the system was safe or not

## How to run?
* use this command in order to run the program in linux terminal
* you might want to change the code if the data set is different
  ```
  clang++ -std=c++11 bankerAlgorithm.cpp
  ./a.out process.txt
  ```
  
## Example output
 Following is the SAFE Sequence:
 P1 -> P3 -> P4 -> P0 -> P2
