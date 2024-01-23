# Write-a-program-to-take-input-of-two-numbers-and-print-their-sum-product-difference

#include <stdio.h>

int main() {
    // Declare variables
    float num1, num2;

    // Input first number
    printf("Enter the first number: ");
    scanf("%f", &num1);

    // Input second number
    printf("Enter the second number: ");
    scanf("%f", &num2);

    // Calculate and print sum
    printf("Sum: %.2f\n", num1 + num2);

    // Calculate and print product
    printf("Product: %.2f\n", num1 * num2);

    // Calculate and print difference
    printf("Difference: %.2f\n", num1 - num2);

    return 0;
}


