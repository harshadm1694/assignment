program to find whether an array is subset of another array with multiple solutions.
-------------------------------------------------------------------------------------------
method1.py -
Use two loops: The outer loop picks all the elements of arr2 one by one.
The inner loop linearly searches for the element picked by the outer loop.
If all elements are found then return 1, else return 0.

method2.py -
Uses Sorting and Binary Search
Sort arr1 using quicksort.
For each element of arr2, do binary search for it in sorted arr1.
If the element is not found then return 0.
If all elements are present then return 1.

method3.py -
Uses Sorting and Merging
Sort both arrays: arr1 and arr2
Used Merge type of process to see if all elements of sorted arr2 are present in sorted arr1.