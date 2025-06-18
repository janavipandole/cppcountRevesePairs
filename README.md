You are given an array of N integers arr, find the count of reverse pairs. 

A pair of indices (i, j) is said to be a reverse pair if both the following conditions are met:

0 <= i < j < N 
arr[i] > 2 * arr[j]
Example 1:

Input:
N = 6
arr = [3, 2, 4, 5, 1, 20]
Output:
3
Explanation:
The Reverse pairs are 
(i)  (0, 4), arr[0] = 3, arr[4] = 1, 3 > 2(1) 
(ii) (2, 4), arr[2] = 4, arr[4] = 1, 4 > 2(1) 
(iii)(3, 4), arr[3] = 5, arr[4] = 1, 5 > 2(1) 
