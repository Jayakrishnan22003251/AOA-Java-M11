
# EX 1A Print All Numbers 
## DATE: 07/08/2025
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1. Start the program and import the Scanner class to take user input.
2. Create a Scanner object to read an integer input N from the user.
3. Check if N is greater than 0; if not, display "Invalid input. N must be greater than 0."
4. Use a for loop to iterate from 1 to N.
5. Print each number separated by a space on the same line.

## Program:
```
/*
Program to print all the numbers from 1 to N
Developed by: JAYAKRISHNAN L B L
Register Number:  212222230052
*/

import java.util.*;
public class PrintNum{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=1;i<=n;i++){
            System.out.print(i+" ");
        }
    }
}

```

## Output:
<img width="602" height="188" alt="image" src="https://github.com/user-attachments/assets/56a17779-e23d-4ca2-ba0a-697b4e5cb841" />



## Result:
The program successfully print all the numbers from 1 to N. 
