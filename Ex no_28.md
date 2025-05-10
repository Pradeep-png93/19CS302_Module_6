# EX 28 C PROGRAM USING ENUM TYPE TO CREATE INTEGER CONSTANTS
## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm
1.	Start.
2.	Declare enum type
3.	Declare all days in a week
4.	Print result
5.	End  

## Program:
```
#include <stdio.h>
enum weekdays {
 Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
};
int main() {
 enum weekdays today = Wednesday;
 if (today == Wednesday) {
 printf("Today is Wednesday.\n");
 }
}
```

## Output:

![image](https://github.com/user-attachments/assets/b5682eff-03e5-4c02-982a-559bd43469f5)


## Result:
Thus the program was executed and the output was verified successfully.
