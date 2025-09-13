# EX15-Recursion


AIM:
    To study and implement the concept of Recursion in C++.

SOFTWARE USED:
    Visual Studio Code (VS Code)

OBJECTIVES:

    - Understand the concept of recursion and how it works in C++.
    - Learn to identify base case and recursive case in problems.
    - Implement recursive functions for mathematical and string-based problems.
    - Compare recursion with iteration in terms of readability, performance, 
      and memory usage.
    - Explore real-world applications of recursion such as divide-and-conquer 
      algorithms, tree traversals, and backtracking.

------------------------------------------------------------
THEORY:

1) DEFINITION
   - Recursion is a programming technique where a function calls itself 
     directly or indirectly to solve a problem. 
   - It breaks down complex problems into smaller subproblems of the same type.

2) KEY COMPONENTS
   - Base Case:
     The stopping condition that prevents infinite recursion.
   - Recursive Case:
     The step where the function calls itself with reduced input, 
     gradually moving toward the base case.

3) HOW IT WORKS
   - Each recursive call is placed on the call stack with its own arguments 
     and local variables.
   - Once the base case is reached, the stack begins to unwind.
   - Results are returned back through each recursive call until 
     the original call completes.

4) TYPES OF RECURSION
   - Direct Recursion:
     A function calls itself directly.
   - Indirect Recursion:
     A function calls another function which calls the first one again.
   - Tail Recursion:
     The recursive call is the last operation in the function.
   - Non-tail Recursion:
     Operations are performed after the recursive call.

5) APPLICATIONS
   - Mathematical problems (factorial, Fibonacci sequence, power functions).
   - Searching and sorting (binary search, quicksort, mergesort).
   - String operations (reverse string, palindrome check).
   - Traversals (trees, graphs).
   - Backtracking (N-Queens, Sudoku solver, pathfinding).

6) COMPARISON WITH ITERATION

   | Aspect           | Recursion                          | Iteration                        |
   |------------------|------------------------------------|----------------------------------|
   | Approach         | Function calls itself              | Uses loops (for, while, do-while)|
   | Memory Usage     | Higher (stack frames per call)     | Lower (loop variables only)      |
   | Code Length      | Shorter, elegant for complex logic | Longer, sometimes harder to read |
   | Performance      | Slightly slower (function overhead)| Usually faster                   |
   | Suitability      | Divide-and-conquer, recursive data | Simple repetitive tasks          |

------------------------------------------------------------
CONCLUSION:
   - Recursion is a powerful concept in C++ that simplifies problems 
     with self-repetitive structures.
   - It enhances readability and reduces code complexity, 
     especially in algorithms like tree/graph traversals and backtracking.
   - However, recursion consumes stack memory and may be inefficient 
     without a clear base case.
   - Iteration is often preferred for performance-sensitive tasks, 
     while recursion is ideal for problems that naturally fit 
     a recursive structure.
   - A balanced approach ensures efficient and elegant solutions.

------------------------------------------------------------
*/
