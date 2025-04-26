# Ex1(E) Stack Operations
## DATE:22.02.25
## AIM:
To write a C function to perform push and pop operation of the stack in the infix to postfix conversion.

## Algorithm
1.	Initialize top as -1 and declare stack as a character array.
2.	To push, increment top and assign the character to stack[top].
3.	To pop, check if top is -1 and return -1 if true.
4.	If not, return 
  

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: G MOULIDHAR
RegisterNumber:  212223240042
PROGRAM:
char stack[100]; int top = -1;
void push(char x)
{
stack[++top] = x;
}

char pop()
{
if(top == -1)
return -1; else
return stack[top--];
}

*/
```

## Output:
![image](https://github.com/user-attachments/assets/d6e79984-59ee-4bcf-b4bc-fb61dd046213)



## Result:
Thus the C program to perform push and pop operation of the stack in the infix to postfix conversion is implemented successfully.
