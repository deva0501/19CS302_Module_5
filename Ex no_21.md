# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
Start.
Declare three variable value of type float.
Prompt the user to enter values.
Read the values using scanf.
Find the area of triangle using formula
End.
## Program:
```
#include <stdio.h> 
int main() { 
    float base, height, area; 
    float *pBase = &base, *pHeight = &height; 
    scanf("%f", pBase); 
    scanf("%f", pHeight); 
    area = 0.5 * (*pBase) * (*pHeight); 
    printf("%.2f\n", area); 
}
```

## Output:

<img width="517" height="187" alt="image" src="https://github.com/user-attachments/assets/6081d5b7-5b62-47f0-98f6-a0b20dc96570" />


## Result:
Thus the program was executed and the output was verified successfully.
