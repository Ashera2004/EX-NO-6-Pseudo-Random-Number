# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.

Seed the random number generator using the current time(i.e) rand(time(0));

Get the number of randon number to generate.

Pass the value for number of iterations and print the numbers.

End the program.


# PROGRAM:
```c
// Pseudorandom Number Generation
// Programmed by Siddarth A S 212224040316
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n;

    printf("Enter how many random numbers to generate: ");
    scanf("%d", &n);

    srand(time(0));

    printf("Generated Random Numbers:\n");

    for (int i = 0; i < n; i++) {
        printf("%d ", rand());
    }

    return 0;
}
```
# OUTPUT:

<img width="1918" height="1198" alt="Screenshot 2026-05-13 123721" src="https://github.com/user-attachments/assets/a9a5408a-0ca0-493e-86ce-5db5e078c142" />


# RESULT:

Thus, Pseudorandom number generation was successfully implemented and executed.
