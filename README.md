# Longest Valid Parentheses

## Problem
Find the length of the longest valid (well-formed) parentheses substring.

## Approach
- Two-pass counter approach.
- First pass: Left to Right.
- Second pass: Right to Left.
- Reset counters when parentheses become invalid.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Language
Java
