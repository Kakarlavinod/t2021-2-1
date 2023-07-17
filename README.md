# PROBLEM-1
# Calculator

This is a simple command-line calculator program written in Java.

## Description

The Calculator program allows you to perform basic mathematical operations such as addition, subtraction, multiplication, and division. It takes user input for the type of operation and the values of the operands, and then calculates and displays the result.

## Usage

To use the Calculator program, follow these steps:

1. Run the program using the `main` method in the `Calculator` class.
2. Enter the type of operation you want to perform (e.g., "addition", "subtraction", "multiplication", "division").
3. Enter the values of the operands (`a` and `b`) as prompted.
4. The program will perform the specified operation and display the result.

Please note that for the division operation, the program checks if the divisor (`b`) is zero and throws an `IllegalArgumentException` in such cases.


# PROBLEM-2
# Number Generator

This is a simple Java program that generates a series of numbers based on user input.

## Description

The Number Generator program takes an integer input `a` and generates a series of numbers based on the following pattern: 1, 3, 5, 7, ...

The program uses Java's `IntStream.rangeClosed()` method to generate a stream of integers from 1 to `a`. Each number in the stream is then transformed using the formula `2 * i - 1` to generate the series of odd numbers.

The generated series is displayed as the output in the format: "Input a = {a}, then output: {series}".

## Usage

To use the Number Generator program, follow these steps:

1. Run the program using the `main` method in the `NumberGenerator` class.
2. Enter the value of `a` when prompted.
3. The program will generate the series of numbers and display the output.



# Problem-3







