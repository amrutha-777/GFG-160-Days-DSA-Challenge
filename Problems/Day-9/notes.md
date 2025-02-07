## Day-9
Problem 16 - Anagram
[View Problem](https://www.geeksforgeeks.org/batch/gfg-160-problems/track/string-gfg-160/problem/anagram-1587115620)
Problem Statement
Check whether two given strings are anagrams of each other, meaning they contain the same characters but in a different order.

# Solution Approach
Convert both input strings into character arrays.
Sort the character arrays using Arrays.sort().
Compare the sorted arrays using Arrays.equals().
Return true if they are equal; otherwise, return false.

# Edge Cases Considered
Different lengths → Directly return false.
Same strings with identical characters → Return true.
Single-character strings → Properly validated.
Code Complexity
Time Complexity:  O(nlogn) due to sorting
Space Complexity: O(1) additional space excluding input storage
