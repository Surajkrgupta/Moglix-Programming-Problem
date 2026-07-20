# Longest Valid Parentheses

## Problem Statement

Given a string `s` containing only the characters `'('` and `')'`, return the **length of the longest valid (well-formed) parentheses substring**.

A valid parentheses substring is one where every opening parenthesis `'('` has a matching closing parenthesis `')'` in the correct order.

# Approach (Stack)

## Idea
Use a **stack** to store the **indices** of parentheses instead of the characters.

- **Time Complexity & Space Complexity:** `O(n)`
