# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE: 05/05/2025
## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to read a file name from user and create that file and insert student
roll numbers in to that file.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## Program:
```
#include <stdio.h>
int main()
{
FILE *p;
char name[100];
int num;
int id;
char text[100];
float m;
scanf("%s",name);
scanf("%d",&num);
p=fopen("name","w");
printf("%s Opened\n",name);
{
scanf("%d %s %f",&id,text,&m);
fprintf(p,"%d %s %f",id,text,m);
}
fclose(p);
printf("Data added Successfully");
```

## Output:

![image](https://github.com/user-attachments/assets/7f19090d-df95-4c0a-b411-7a926ff02ebf)


## Result:
Thus the program was executed and the output was verified successfully.
