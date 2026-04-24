# menu-driven-calculator-using-switch-statement
 Write a C program for menu driven calculator using switch statement

Program:

```
#include <stdio.h>

int main() {
    int choice;
    float a, b;

    printf("Enter two numbers: ");
    scanf("%f %f", &a, &b);

    printf("\n--- Calculator ---\n");
    printf("1. Addition\n");
    printf("2. Subtraction\n");
    printf("3. Multiplication\n");
    printf("4. Division\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    switch (choice) {
        case 1:
            printf("Result = %.2f", a + b);
            break;

        case 2:
            printf("Result = %.2f", a - b);
            break;

        case 3:
            printf("Result = %.2f", a * b);
            break;

        case 4:
            if (b != 0)
                printf("Result = %.2f", a / b);
            else
                printf("Division by zero not allowed");
            break;

        default:
            printf("Invalid choice");
    }

    return 0;
}
```

Output:

Addition:

<img width="1865" height="1004" alt="image" src="https://github.com/user-attachments/assets/68bbc1ba-592b-4240-aed6-1b8f5a5c5a79" />


Subtraction:

<img width="1862" height="1020" alt="image" src="https://github.com/user-attachments/assets/9aa1f649-1328-480a-b6fd-94b24454145d" />


Multiplication:

<img width="1870" height="987" alt="image" src="https://github.com/user-attachments/assets/4fbbe7c5-c2b3-4e84-9712-c833e2e20a11" />


Division:

<img width="1854" height="1011" alt="image" src="https://github.com/user-attachments/assets/e3a63c41-ecf6-4bab-96de-d9b9393767ab" />
