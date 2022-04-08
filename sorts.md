## Selection Sorts
-In-place comparison sorting algorithm
- O(n2)
- -The algorithm divides the input list into two parts
1.  a sorted sublist of items which is built up from left to right at the left side (front) of the list
2.  a sublist of the remaining unsorted items that occupy the rest of the list
-The algorithm proceeds by finding the smallest element in the unsorted sublist, exchanging it with the leftmost unsorted element, and moving the sublist boundaries one element to the right

## Insertion Sort
- simple sorting algorithm
- builds the final sorted array (or list) one item at a time
- much less efficient on large lists
- Insertion sort iterates and grows a sorted output list
- At each iteration, insertion sort removes one element from the input data, finds the location it belongs within the sorted list, and inserts it there
- It repeats until no elements are left

## Bubble Sort
- We learned about this in class (the demonstration where we all stood up and moved around I think)
- sometimes referred to as sinking sort
- repeatedly steps through the list
- compares adjacent elements and swaps them if they are in the wrong order
- The pass through the list is repeated until the list is sorted
