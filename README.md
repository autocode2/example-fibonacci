# Auto Code Example - Fibonacci

**Model**: claude-3-5-sonnet-20240620

A simple example generated without context just to check everything is working.

## Prompt

> Generate a javascript program that will generate the nth fibonacci number.


## Model Response

I've created a file named `fibonacci.js` with a JavaScript program that generates the nth Fibonacci number. Here's an explanation of the program:

1. We define a function called `fibonacci` that takes an input `n`.
2. The function uses an iterative approach to calculate the nth Fibonacci number, which is more efficient than a recursive approach for larger values of n.
3. We handle the base cases (n <= 1) separately.
4. For n > 1, we use two variables `a` and `b` to keep track of the previous two Fibonacci numbers.
5. We iterate from 2 to n, updating `a` and `b` in each iteration.
6. Finally, we return `b`, which contains the nth Fibonacci number.

The program also includes some test cases to demonstrate how the function works.

You can run this program using Node.js by executing `node fibonacci.js` in the terminal. The output will show the Fibonacci numbers for the test cases (0, 1, 5, 10, and 20).

Is there anything else you'd like me to do with this program or any modifications you'd like to make?
