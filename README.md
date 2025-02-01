# Python ZeroDivisionError Handling

This repository demonstrates a common Python programming error: the `ZeroDivisionError` that occurs when dividing by zero. The error arises when trying to calculate the average of an empty list. This repository provides a solution that gracefully handles this edge case.

## Bug
The original code (`bug.py`) attempts to calculate the average of a list of numbers. However, if the list is empty, it raises a `ZeroDivisionError` because it attempts to divide by the length of an empty list (which is 0).

## Solution
The solution (`bugSolution.py`) adds a check to handle the case of an empty list. If the list is empty, it returns 0 as the average. This prevents the `ZeroDivisionError` and provides a more robust solution.

## How to Run
1. Clone the repository.
2. Run `bug.py` to see the original error.
3. Run `bugSolution.py` to see the corrected code in action.