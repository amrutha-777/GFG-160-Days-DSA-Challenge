### DAY-8
### Minimize the Heights II (Problem 9)

- **Difficulty**: Medium
- **Accuracy**: 15.06%
- **Problem Link**: [\[View Problem\](https://www.geeksforgeeks.org/batch/gfg-160-problems/track/arrays-gfg-160/problem/minimize-the-heights3351)]()

#### Approach:
- This problem involves reducing the height difference between towers using at most `K` modifications to either increase or decrease the tower heights.
- I started by sorting the array, then iterating through it to calculate the minimum and maximum height differences after modifying the towers within the given range of `k`.
- The goal is to minimize the difference between the tallest and shortest tower after the modifications.

#### Learnings:
- This problem strengthened my understanding of sorting and greedy approaches for optimization.
- It also helped me better handle edge cases and understand the impact of modifications on the overall outcome.

EXAMPLE:
arr[] = [1, 5, 8, 10], K = 2

After sorting: [1, 5, 8, 10]

Possible height adjustments:
- Tower 1: Increase (1 + 2), Decrease (1 - 2)
- Tower 2: Increase (5 + 2), Decrease (5 - 2)
- Tower 3: Increase (8 + 2), Decrease (8 - 2)
- Tower 4: Increase (10 + 2), Decrease (10 - 2)

Compute the minimum difference between the tallest and shortest towers.
