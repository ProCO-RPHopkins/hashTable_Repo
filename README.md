# Longest Consecutive Sequence - W9D4

Understand Problem
-Find the length of the longest consecutive sequence in unsorted array
-Input: Unsorted array (i.e. nums)
-Output: Integer representing of longest consecutive sequence
-Constraints: Must run in O(n) time complexity (i.e., can only iterate list once based on length of input array (i.e., n))

Approach
-Hash set to solve problem efficiently using O(n) time complexity

Algorithm
-Convert array into a set where each element only appears once
-Iterate through set to determine beginning of sequence. Sequence begins with number that isn't already in box
-Count length of consecutive numbers before running into duplicate (duplicates already removed so existing array is simply counted)
-Keep track of longest sequence, which will be output
