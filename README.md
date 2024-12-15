# Elixir Enum.each and throw Unexpected Behavior

This repository demonstrates an unexpected behavior when using `throw` within an `Enum.each` loop in Elixir. The example code shows how `throw` immediately terminates the entire function, not just the `Enum.each` loop. This is different from the behavior one might expect from languages with similar constructs like `for` loops.

The solution illustrates how to modify the code to achieve the expected result using `try...catch` for error handling within the loop or choosing a different enumeration function like `Enum.reduce` or `for`.

This example highlights a subtle difference in Elixir's behavior and can help developers avoid common pitfalls when working with `Enum.each` and exception handling.