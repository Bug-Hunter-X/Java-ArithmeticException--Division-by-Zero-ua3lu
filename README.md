# Java Uncommon Bug: ArithmeticException

This repository demonstrates a simple Java program that throws an `ArithmeticException`. This exception is thrown when an attempt is made to divide an integer by zero.

## The Bug
The `UncommonBug.java` file contains the buggy code. The program attempts to divide an integer variable `x` by zero, resulting in an `ArithmeticException` at runtime.

## The Solution
The `UncommonBugSolution.java` file provides a solution to the problem by adding a check to avoid division by zero.

## How to Run
1. Clone this repository.
2. Compile and run the `UncommonBug.java` and `UncommonBugSolution.java` files using a Java compiler (like javac) and interpreter (like java).

Observe the behavior and learn how to handle potential division-by-zero errors in your Java programs.  This scenario might be considered uncommon, but it highlights how important input validation is to robust code.