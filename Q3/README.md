# Approach:

To solve this problem efficiently, we use the mathematical formula for the sum of the first N natural numbers.

Formula

Sum of numbers from 1 to N = N * (N + 1) / 2

Since the sequence should contain numbers from 1 to (n+1):
Expected Sum = (n + 1) * (n + 2) / 2
Then we calculate the actual sum of the array elements.
Missing Number = Expected Sum - Actual Sum



# Run the program using:

node missingNumber.js