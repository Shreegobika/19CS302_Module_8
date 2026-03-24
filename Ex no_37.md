# # Hackerrank problem - 2

Your task is to take two numbers of int data type, two numbers of float data type as input and output their sum:

Declare 4 variables: two of type int and two of type float.

Read 2 lines of input from stdin (according to the sequence given in the 'Input Format' section below) and initialize your variables.

Use the + and - operator to perform the following operations:

Print the sum and difference of two int variable on a new line.

Print the sum and difference of two float variable rounded to one decimal place on a new line.

## EX 31 C program to find the smallest among three numbers using Structure.
## DATE:23/05/2025
## AIM:
To write a C program to find the smallest among three numbers using Structure.

## Algorithm
1.Start the program and define a structure with three integer fields.

2.Declare a structure variable to store the three numbers.

3.Read the values of the three numbers from the user.

4.Compare the three numbers to find the smallest.

5.Display the smallest number and end the program.

## Program:
```
/* C program to find the smallest among three numbers using Structure.

*/ #include <stdio.h>

struct Numbers { int num1, num2, num3; };

int main() { struct Numbers n;

printf("Enter three numbers: ");
scanf("%d %d %d", &n.num1, &n.num2, &n.num3);

int smallest = n.num1;

if(n.num2 < smallest)
{
    smallest = n.num2;
}

if(n.num3 < smallest)
{
    smallest = n.num3;
}

printf("The smallest number is: %d\n", smallest);

return 0;
}
```

## Output:
<img width="375" height="214" alt="image" src="https://github.com/user-attachments/assets/736f3c3a-6840-4c39-8021-e681a5f415c8" />

## Result:
Thus the program was executed and the output was verified successfully.Uploading image.png…
