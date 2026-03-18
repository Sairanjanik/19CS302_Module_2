# EX 7 C Program to Print binary number pattern of n rows and m columns using loop.
## AIM:
To write a C Program to Print binary number pattern of n rows and m columns using loop.

## Algorithm
1. Read number of rows and columns from the user.
2. Use an outer loop to repeat for each row.
3. Inside the outer loop, use an inner loop to print '*' for each column.
4. After each row, print a newline to move to the next row.
5. End the program.


## Program:
```
/*
Program to Print binary number pattern of n rows and m columns using loop.
Developed by: Sai Ranjani K
RegisterNumber:  212222060210
#include <stdio.h>
int main() 
{
    int a,b,i,j;
    scanf("%d %d",&a,&b);
    for(i=0;i<a;i++)
    {
      for(j=0;j<b;j++)
      {
         printf("*");
      }
      printf("\n");
    }
    
    return 0;
}
*/
```

## Output:


![image](https://github.com/user-attachments/assets/ea112e81-375c-43ef-8a98-0458526824ff)


## Result:
Thus the program was executed and the output was verified successfully.
