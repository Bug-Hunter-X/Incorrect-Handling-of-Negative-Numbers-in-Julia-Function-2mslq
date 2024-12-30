# Incorrect Handling of Negative Numbers in Julia Function

This repository contains a Julia function that demonstrates an issue with handling negative numbers. The function `my_function` is designed to return the square of a positive number and 0 for non-positive numbers, but it returns unexpected results for negative inputs. The `bug.jl` file contains the erroneous code, while `bugSolution.jl` provides a corrected version.

## Bug Description
The function fails to correctly handle the condition where the input is a negative number. This leads to incorrect output for such cases.

## Solution
The solution involves adding a check for negative inputs within the conditional statement to ensure the function behaves as intended. The `bugSolution.jl` file provides the corrected implementation, which addresses the issue.  This demonstrates a common error in handling conditional logic in programming languages.