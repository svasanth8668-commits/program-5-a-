# program-5-a-
C module 5
EX NO:5-a) Multiplication of three numbers using pointers. 

Date:19/10/2025 

Name: VASANTH S 

Ref no: 25017538

AIM:
To write a C program to multiply three numbers using pointers.

ALGORITHM:
1) Get three numbers as inputs from the user.
2) Assign pointer variables for each inputs.
3) print the result of multiplication using printf() funtion.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,num3;
    scanf("%d %d %d",&num1,&num2,&num3);
    int *ptr1=&num1,*ptr2=&num2,*ptr3=&num3;
    printf("%d * %d * %d= %d",num1,num2,num3,*ptr1**ptr2**ptr3);
}
```

OUTPUT:



<img width="445" height="238" alt="Screenshot 2025-10-20 195814" src="https://github.com/user-attachments/assets/e9d873c5-1f40-44b4-b25c-f29ded6d9e4b" />



RESULT:

Thus the C program to multiply three numbers using pointers is executed successfully.




