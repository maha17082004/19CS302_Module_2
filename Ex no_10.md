# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
Start
Declare function factorial(int n)
Initialize fact = 1
Loop from i = 1 to n
Multiply fact = fact * i
Return fact
In main(), declare num
Read num from user
Call factorial(num) and store in result
Print result
End  

## Program:
```
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

```

## Output:
<img width="497" height="188" alt="image" src="https://github.com/user-attachments/assets/07d23af1-c28a-47c0-bc69-2ef5de3e5ae6" />

## Result:
Thus the program was executed and the output was verified successfully.
