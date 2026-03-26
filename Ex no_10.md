# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm

1. Start
   
2.Declare function factorial(int n)

3.Initialize fact = 1

4.Loop from i = 1 to n

5.Multiply fact = fact * i

6.Return fact

7.In main(), declare num

8.Read num from user

9.Call factorial(num) and store in result

10.Print result

11.End
  

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
#include <stdio.h>
int factorial(int n) {
    int fact = 1;
    for (int i = 1; i <= n; ++i) {
        fact *= i;
    }
    return fact;
}
int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    int result = factorial(num);
    printf("Factorial of %d is %d\n", num, result);
    return 0;
}

Developed by: DUDEKULA HASEENA
RegisterNumber:212222063004 
*/
```

## Output:
<img width="650" height="262" alt="image" src="https://github.com/user-attachments/assets/6630d3e2-6970-4fcd-ba87-16b2aaa009d5" />

## Result:
Thus the program was executed and the output was verified successfully.
