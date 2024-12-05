# Ada Exit Statement Gotcha

This example demonstrates a potential pitfall with Ada's `exit` statement when used within loops.  The `exit` statement only exits the innermost loop, which might not be what's intended. If the inner loop condition is met and the loop exits, the subsequent code after the loop might not be executed as expected, leading to unexpected behaviour.

The solution shows how to use a boolean variable to control the loop's termination from within the inner loop, enabling more flexible control flow and avoiding unexpected behaviour.