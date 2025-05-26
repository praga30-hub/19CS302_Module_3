# EX 14 C program to delete first element in an array.

## AIM:
To write a C program to delete first element in an array.

## Algorithm
1. Start.
2. Define a variables i,j,a.
3. Read the value using scanf.
4. Ask the user to make an input
5. Print out the answer
6. End.
      

## Program:
```
#include<stdio.h> 
int main()
{
int i,n,a[10];
scanf("%d",&n); 
for(i=0;i<n;i++)
{
scanf("%d",&a[i]);
}
for(i=1;i<n;i++) 
printf("%d ",a[i]);
}

```

## Output:
![image](https://github.com/user-attachments/assets/540f2c37-01c6-4923-8b0b-bdf1420e2014)



## Result:
Thus the program was executed and the output was verified successfully.
