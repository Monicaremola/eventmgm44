#include <stdio.h>

int main() {
    int num1, num2, sum;

    // Asking for input
    printf("Enter first number: ");
    scanf("%d", &num1);
    printf("Enter second number: ");
    scanf("%d", &num2);

    // Calculating sum
    sum = num1 + num2;

    // Displaying the sum
    printf("Sum: %d\n", sum);

    return 0;
}
