
## Approach (Brute Force)

- Traverse each element of the array.
- For every element, check all elements to its right.
- If any element on the right is greater than the current element, it is not a leader.
- If no greater element is found, the current element is a leader.

## Logic

For every element:

- Compare it with all elements on the right side.
- Keep track of whether a greater element exists.
- If no greater element exists, add/print the element as a leader.

## Complexity Analysis

- **Time Complexity:** O(n²)  
  - Each element is compared with the elements on its right side.

- **Space Complexity:** O(1)  
  - No extra data structure is used.

## Key Learning

This problem helps understand:
- Nested loop traversal
- Comparing an element with all elements after it
- Finding patterns to optimize from brute force to O(n) solutions
