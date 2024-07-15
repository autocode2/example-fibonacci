# Auto Code Example - Fibonacci

**Model**: claude-3-haiku-20240307

A simple example generated without context just to check everything is working.

## Prompt

> Generate a javascript program that will generate the nth fibonacci number.

## Model Response

Okay, let's generate a JavaScript program to calculate the nth Fibonacci number.
Creating file:  fibonacci.js
The key steps are:

1. Define a `fibonacci` function that takes an integer `n` as input.
2. If `n` is 0 or 1, return `n` as the Fibonacci number.
3. Otherwise, recursively call `fibonacci(n-1)` and `fibonacci(n-2)` and return their sum.
4. Log the 10th Fibonacci number to the console to test the function.

This implements the classic recursive definition of the Fibonacci sequence, where each number is the sum of the previous two. You can call the `fibonacci` function with any positive integer `n` to get the nth Fibonacci number.

Let me know if you have any other questions!
