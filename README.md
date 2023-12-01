# Maximizing-The-Final-Element

Given an array of integers, perform certain operations in order to satisfy some constraints. The constraints are as follows:

- The first array element must be 1.
- For all other elements, the difference between adjacent integers must not be greater than 1. In other words, for 1 ≤ i<n, arr[i] - arr[i-1] ≤ 1.

To accomplish this, the following operations are available:

• Rearrange the elements in any way.

• Reduce any element to any number that is at least 1.

What is the maximum value that can be achieved for the final element of the array by following these operations and constraints?

# Example

arr = [3, 1, 3, 4]

1. Subtract 1 from the first element, making the array [2, 1, 3, 4].

2. Rearrange the array into [1, 2, 3, 4].

3. The final element's value is 4, the maximum value that can be achieved. Therefore, the answer is 4.
