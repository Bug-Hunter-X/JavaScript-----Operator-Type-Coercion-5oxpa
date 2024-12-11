# JavaScript '+' Operator Type Coercion
This example demonstrates a common, yet easily overlooked, issue in JavaScript related to the '+' operator's behavior with different data types.  The '+' operator will concatenate strings instead of performing numerical addition if either operand is a string.

## Problem
The function `foo` is intended to add two numbers. However, it doesn't explicitly check for the types of input, leading to unexpected behavior when strings are passed as arguments.

## Solution
To avoid this issue, type checking and explicit type conversion should be implemented to ensure both operands are numbers before the addition takes place.