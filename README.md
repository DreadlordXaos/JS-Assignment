# JS Assignment 

## Overview
This repository contains solutions to six JavaScript problems implemented using plain JavaScript inside HTML files.
Input is taken using `prompt()` and output is displayed using `alert()` as specified in the assignment.

## File Structure
* q1.html – Digit Gatekeeper
* q2.html – Roll-Seed Lock
* q3.html – Mirror Corridor
* q4.html – Fare Calculator
* q5.html – Skipping Numbers
* q6.html – Contest Score Judge

## How to Run
1. Open any `.html` file in a web browser
2. Provide input through prompts
3. View output in alert dialogs
## Approach and Complexity

### Question 1: Digit Gatekeeper
Iterate from L to R, filter numbers divisible by K, exclude numbers containing 0, compute digit sum, and check if it is prime.
Time Complexity: O(N × D)
Space Complexity: O(1)

### Question 2: Roll-Seed Lock
Apply the transformation rule three times based on parity, then check if the result is a three-digit number and if its middle digit equals the seed.
Time Complexity: O(1)
Space Complexity: O(1)

### Question 3: Mirror Corridor
Check values of X from 0 to 100000 such that N + X is a palindrome and divisible by K. Return the smallest valid X.
Time Complexity: O(100000 × D)
Space Complexity: O(1)

### Question 4: Fare Calculator
Compute fare using given conditions, apply adjustments, and round up to the nearest multiple of 5.
Time Complexity: O(1)
Space Complexity: O(1)

### Question 5: Skipping Numbers
Iteratively sum numbers excluding multiples of (seed + 2) until the sum reaches or exceeds N.
Time Complexity: O(M)
Space Complexity: O(1)

### Question 6: Contest Score Judge
Calculate score using the formula, apply constraints, and determine pass or fail.
Time Complexity: O(1)
Space Complexity: O(1

## Notes

All solutions follow the problem constraints and avoid hardcoding. Only basic JavaScript concepts are used.
