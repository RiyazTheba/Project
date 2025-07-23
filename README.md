#include <stdio.h>

// Function to calculate simple interest
float calculateSimpleInterest(float principal, float rate, float time) {
    float si;
    si = (principal * rate * time) / 100;
    return si;
}

int main() {
    float P, R, T, interest;

    // Taking input from the user
    printf("Enter Principal amount: ");
    scanf("%f", &P);

    printf("Enter Rate of Interest: ");
    scanf("%f", &R);

    printf("Enter Time (in years): ");
    scanf("%f", &T);

    // Calling function to calculate SI
    interest = calculateSimpleInterest(P, R, T);

    // Displaying result
    printf("Simple Interest = %.2f\n", interest);

    return 0;
}# Project
