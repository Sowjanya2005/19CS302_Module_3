# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE: 20-03-2025
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
1. Start.
2. Declare a integer variable
3. Define a function named dectobin.
4. Return the integer.
5. Read the value using scanf.
6. Convert decimal to binary value.
7. Print the dectobin
8. End.    

## Program:
```
/*
Program to C Program to convert a given decimal value to binary using function without arguments with return type.
Developed by: Sowjanya A
RegisterNumber: 212222060250
*/
#include<stdio.h>
Int dectobin(int d){
int bin =0,base=1,rem; 
while(d>0)
{
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10;
}
printf(" = %d in binary",bin); 
return 0;
}
int main()
{
int dec; 
scanf("%d",&dec);
printf("%d in decimal",dec); 
dectobin(dec);
return 0;

```

## Output:

![image](https://github.com/user-attachments/assets/9d0cc919-7417-45ab-bb86-a3d9a9cc2ff7)

## Result:
Thus the program was executed and the output was verified successfully.
