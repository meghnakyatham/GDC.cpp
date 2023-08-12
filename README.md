# GDC.cpp
**GCD Calculation Program using Euclidean Algorithm**

This C++ program calculates the Greatest Common Divisor (GCD) of two input numbers using the Euclidean algorithm. The GCD is the largest positive integer that divides both input numbers without leaving a remainder. The program takes two integers as input and iteratively applies the Euclidean algorithm to find their GCD.

**How to Use:**

1. Compile the Program:
   Make sure you have a C++ compiler installed on your system. You can useG+++, Visual C++, or any other C++ compiler of your choice to compile the program. For example, using G+++:
   ```
   g++ gcd_calculator.cpp -o gcd_calculator
   ```

2. Run the Program:
   Execute the compiled program and follow the on-screen instructions to input two numbers.
   ```
   ./gcd_calculator
   ```

3. Input Numbers:
   Enter two integers when prompted by the program.

4. Output:
   The program will calculate and display the GCD of the input numbers using the Euclidean algorithm.

**Algorithm Explanation:**

The program uses the Euclidean algorithm to calculate the GCD of two numbers. The algorithm involves iteratively subtracting the smaller number from the larger number until both numbers become equal. The final common value is the GCD of the original two numbers.

**Program Breakdown:**

1. Include necessary headers:
   The program includes the `<iostream>` header to use input/output stream functions.

2. `main()` Function:
   - Declares two integer variables, `m` and `n`, to store the input numbers.
   - Outputs a prompt to enter two numbers.
   - Reads the two input numbers using `cin`.

3. GCD Calculation Loop:
   - Enters a while loop that continues until `m` becomes equal to `n`.
   - Inside the loop:
     - Checks if `m` is greater than `n`. If true, subtracts `n` from `m`.
     - Checks if `n` is greater than `m`. If true, subtracts `m` from `n`.

4. Display GCD:
   - After the loop, the program outputs the calculated GCD (which is now stored in either `m` or `n`).
   
5. Return:
   - The `main()` function returns 0 to indicate successful program execution.

**Note:** The program assumes that the input numbers are positive integers. If you enter non-positive integers, the program behavior may not be accurate.

