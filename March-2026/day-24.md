## Date: 24 March 2026

### What I Learned
- Practiced Logarithmic Inequalities and Logarithmic Equations for NIMCET  
- Strengthened understanding of sliding window and stack-based problems  

### What I Practiced / Built
- Solved LeetCode Problem 239 (Sliding Window Maximum)  
  - Used deque to maintain elements of the current window  
  - Removed smaller elements from the back to keep maximum at front  
  - Stored maximum for each window in a result vector  
  - Optimized from brute force to O(n) solution  

- Solved LeetCode Problem 84 (Largest Rectangle in Histogram)  
  - Used stack to find next smaller element on left and right  
  - Created two arrays to store boundaries  
  - Calculated width = right - left - 1  
  - Computed area for each bar and tracked maximum  

### Problems Faced
- Multiple mistakes while implementing stack logic in histogram problem  
- Managing edge cases and indices correctly  

### Fix / Takeaway
- Learned importance of monotonic stack patterns  
- Improved debugging skills through trial and error  
- Understood how optimized data structures (deque, stack) reduce complexity significantly  
