# LOOPS

This repository demonstrates the use of loops in C programming.

## Overview

Loops are fundamental constructs in C that allow you to repeatedly execute a block of code as long as a specified condition is true. They are essential for tasks such as iterating through arrays, processing input, and performing repetitive calculations.

## Types of Loops in C

1. **for loop**
   - Used when the number of iterations is known.
   - Syntax:
     ```c
     for(initialization; condition; increment/decrement) {
         // code block to be executed
     }
     ```
   - Example:
     ```c
     for(int i = 0; i < 10; i++) {
         printf("%d\n", i);
     }
     ```

2. **while loop**
   - Used when the number of iterations is not known in advance.
   - Continues as long as the condition is true.
   - Syntax:
     ```c
     while(condition) {
         // code block to be executed
     }
     ```
   - Example:
     ```c
     int i = 0;
     while(i < 10) {
         printf("%d\n", i);
         i++;
     }
     ```

3. **do...while loop**
   - Similar to the while loop but checks the condition after executing the code block at least once.
   - Syntax:
     ```c
     do {
         // code block to be executed
     } while(condition);
     ```
   - Example:
     ```c
     int i = 0;
     do {
         printf("%d\n", i);
         i++;
     } while(i < 10);
     ```

## Usage

Explore the code samples in this repository to understand how each loop works in different scenarios. You can compile and run the programs to see how loops function and how they can be used to solve various programming problems.

## Contributing

Feel free to add more examples demonstrating advanced loop usage, such as nested loops, breaking out of loops, and using loops with arrays.

## License

This repository is open source and available under the MIT License.
