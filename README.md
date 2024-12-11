# CSS `calc()` Misuse in Flexbox

This repository demonstrates a common error when using the `calc()` function in CSS, specifically within flexbox layouts. The issue arises from the way `calc()` interacts with percentage values and the automatic sizing behavior of flex items.  The provided code illustrates the problem and its solution.

## Bug:
The initial CSS (`bug.css`) shows how incorrect usage of `calc()` can lead to unexpected results.  The solution is provided in `bugSolution.css`.

## Solution:
The solution involves a careful approach to percentage calculations and considering the context in which `calc()` is used within a flexbox layout.