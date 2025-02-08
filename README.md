# Daily-Leetcode-problem-solution2
PROBLEM 

Design a number container system that can do the following:
Insert or Replace a number at the given index in the system.
Return the smallest index for the given number in the system.
Implement the NumberContainers class:
NumberContainers() Initializes the number container system.
void change(int index, int number) Fills the container at index with the number. If there is already a number at that index, replace it.
int find(int number) Returns the smallest index for the given number, or -1 if there is no index that is filled by number in the system.

Intuition

An efficient implementation of the NumberContainers class using C++ STL containers like unordered_map and map

Approach

Use an unordered_map indexToNumber to store the mapping of indices to numbers.
Use a map of sets numberToIndices to store numbers as keys and their indices in a sorted set.

Complexity

Time complexity:
O(log n)

Space complexity:
O(1)
