# LOOPS IN CPP
Aim: To study and implement C++ decision making statements Loops

Tools Used: VS Code or Programiz online cpp compiler

# Theory
Loops in C++ automate repetitive tasks, making code efficient and concise. The for loop is ideal when iteration count is known, using initialization, condition, and update. The while loop runs as long as a condition holds true, useful for uncertain iterations. Both eliminate redundancy, enhancing readability and performance. Choosing the right loop depends on the problem's structure and data handling needs.
## for Loop
The for loop is best when the number of iterations is predetermined. Its structure consists of three key parts:

```
for(initialization; condition; increment/decrement) {
    // code to be repeated
    }
```

-Initialization – Sets the starting value of the loop counter.
-Condition – Keeps the loop running while true.
-Increment/Decrement – Updates the counter after each iteration.

This loop is efficient for count-based tasks like array traversal, number sequences, and fixed repetitions. Its compact syntax reduces redundancy, making code cleaner and easier to debug. Use a for loop when iteration bounds are clearly defined.
## while Loop
The while loop runs indefinitely as long as its condition remains true, making it ideal for unpredictable iterations.

```
while(condition) {
// code to be repeated
}
```

-Condition-checked first – If false initially, the loop never executes.
-No fixed count – Perfect for user input, file reading, or dynamic conditions.
-Manual update required – The loop continues until the condition becomes false.

Unlike for loops, it doesn’t auto-increment, so ensure the condition changes inside the loop to avoid infinite execution. Best for scenarios where termination depends on runtime factors.
## Nested for Loops
A nested for loop places one loop inside another, enabling multi-level repetition. It's ideal for grid-based operations, 2D arrays, or pattern printing, where each level handles a distinct dimension. Proper indentation ensures clarity when working with nested iterations.

```
for(initialization1; condition1; update1) {
    for(initialization2; condition2; update2) {
        // inner loop statements
    }
    // outer loop statements
}
```
# Pattern Printing 
Pattern printing in C++ utilizes nested loops to create structured shapes using characters, numbers, or symbols.

## Common Pattern Types
-Simple Triangle
-Inverted Triangle
-Flipped Triangle
-Pyramid
-Diamond
-Hourglass
-Number Patterns
-Alphabet Patterns

# Program 1: Print Even Numbers (0-10) using for Loop
Prints even numbers from 0 to 10 using a for loop and checks divisibility by 2.

Algorithm:
1. Start
2. Loop i from 0 to 10:
3. If i % 2 == 0, print i.
4. Stop

# Program 2: Print a word 5 Times using for Loop
Prints "program" five times using a for loop with a fixed iteration count.

Algorithm:
1. Start
2. Loop i from 0 to 4:
3. Print "SIT".
4. Stop

# Program 3: Print Numbers (1-20) using while Loop
Uses a while loop to print numbers from 1 to 20.

Algorithm:
1. Start
2. Initialize n = 1.
3. While n <= 20:
4. Print n.
5. Increment n.
6. Stop

# Program 4: Password Checker using while Loop
Sets a password (min 8 chars), confirms it, and allows login attempts until exit.

Algorithm:
1. Start
2. Prompt for password (repeat if < 8 chars).
3. Confirm password (repeat if mismatch).
4. Loop for login attempts:
5. Enter password or 'x' to exit.
6. Grant access if correct, else retry.
7. Stop

# Program 5: Reverse a Number using while Loop
Reverses an input number using modulus (%) and division (/).

Algorithm:
1. Start
2. Input a number.
3. While number > 0:
4. Extract last digit (% 10).
5. Print digit.
6. Remove digit (/ 10).
7. Stop

# Nested for Loop Demonstration
Shows nested loop execution with an outer loop (2 runs) and inner loop (3 runs).

Algorithm:
1. Start
2. Outer loop (i = 1 to 2).
3. Inner loop (j = 1 to 3).
4. Print i and j.
5. Stop

# Pattern Programs
**1. Simple Pyramid**
Prints a left-aligned star triangle.

Algorithm:
-Loop rows (i = 1 to n).
-Loop columns (j = 1 to i).
-Print * per row.

**2. Flipped Pyramid**
Prints a right-aligned star triangle.

Algorithm:
-Loop rows (i = 1 to n).
-Print n-i spaces.
-Print i stars.

**3. Inverted Pyramid**
Prints a descending left-aligned star triangle.

Algorithm:
-Loop rows (i = 1 to n).
-Loop columns (j = i to n).
-Print * per row.

**4. Floyd’s Triangle (Numbers)**
Prints incremental numbers row-wise.

Algorithm:
-Initialize counter c = 1.
-Loop rows (i = 1 to n).
-Loop columns (j = 1 to i).
-Print and increment c.

**5. Floyd’s Triangle (Alphabets)**
Prints incremental letters row-wise.

Algorithm:
-Initialize ch = 'A'.
-Loop rows (i = 1 to n).
-Loop columns (j = 1 to i).
-Print and increment ch.

**6. Hourglass Pattern**
Combines inverted and upright pyramids.

Algorithm:
-Top half: Decreasing stars with spacing.
-Bottom half: Increasing stars with spacing.

# Conclusion
Hence, we used multiple types of loops and excuted some basic codes and varieties of patterns in CPP.
