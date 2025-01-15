# Base Sum Analyzer

## Overview
**Base Sum Analyzer** is a C program that calculates the sum of digits of a non-negative integer in various bases (from base 10 down to base 2) and identifies the bases that yield the greatest and least sums.
## Features
- **Sum of Digits Calculation**:
  - Computes the sum of digits of a number in bases ranging from 10 to 2.
  - Displays the results for each base.

- **Max/Min Identification**:
  - Finds the base with the greatest and least sums of digits for the entered number.

- **User-Friendly Interface**:
  - Ensures input is a non-negative integer.
  - Handles invalid or non-numeric input gracefully.

- **Repeat Functionality**:
  - Allows users to process multiple numbers in a single session.

## How to Use
### Compilation
1. Ensure you have a C compiler (e.g., GCC) installed.
2. Compile the program using the following command:
   ```bash
   gcc -o base_sum_analyzer base_sum_analyzer.c -Wall -g
   ```

### Running the Program
1. Run the compiled program:
   ```bash
   ./base_sum_analyzer
   ```
2. Follow the on-screen prompts:
   - Enter a non-negative integer to analyze.
   - View the sum of digits in different bases and the identified max/min bases.
   - Choose whether to analyze another number or exit the program.

## Example Execution
#### Input:
```
Enter an integer (non-negative): 15
```
#### Output:
```
Sum of Digits:
Base 10 is: 6
Base 9 is: 7
Base 8 is: 8
Base 7 is: 3
Base 6 is: 5
Base 5 is: 3
Base 4 is: 6
Base 3 is: 3
Base 2 is: 4

15 has the greatest sum of digits in base 8
and least sum of digits in base 7

Input another number? Y/N
```

## Development Notes
- Written and tested in C.
- Verified for proper handling of invalid inputs, including non-numeric and negative values.
- Designed to loop until the user chooses to exit.

## Author
Nicholas Minieri
