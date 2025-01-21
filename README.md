This repository demonstrates an uncommon bug in TypeScript involving an unexpected early return from a function due to a misplaced `return` statement within a loop. The `printNumbers2` function is intended to print numbers from 1 to n, but it prematurely exits when `i` reaches 3 because of the `return` statement inside the loop. This highlights a common error where developers might accidentally place a `return` statement inside a loop, disrupting the intended logic. The solution shows how to correct the code to achieve the desired behavior, printing numbers up to n without prematurely terminating the loop.