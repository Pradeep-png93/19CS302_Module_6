# EX 29 C PROGRAM TO FIND THE MINIMUM NUMBER USING CALLOC().
## AIM:
To write a C program to create two float variables using calloc() and find minimum among them.

## Algorithm
1.	Start.
2.	Initialize two variables value of calloc().
3.	Prompt the user to enter values.
4.	Read the values using scanf.
5.	Find minimum and print result
6.	End.

## Program:
```
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *num1, *num2, minimum;
 num1 = (int *)calloc(1, sizeof(int));
 num2 = (int *)calloc(1, sizeof(int));
 num1= 5.8 , num2 = 6.5;
 minimum = (*num1 < *num2) ? *num1 : *num2;
 printf("%d\n", minimum);
 free(num1);
 free(num2);
```

## Output:

![image](https://github.com/user-attachments/assets/e2b3fb17-f4cc-4563-8b56-2e5e41efe769)


## Result:
Thus the program was executed and the output was verified successfully.
