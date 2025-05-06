# CMPS 2200 Recitation 09

## Answers

**Name:** Jaedan Curcio



Place all written answers from `recitation-09.md` here for easier grading.



- **2)**
  - In the worst case scenario, each node (n) has a edge between every pair, so the total edges is approximately n^2.
As a result, performing heap operations (log n) with n^2 edges gives a worst case work of O(n^2 log n)

- **4)**
  - This algorithm gives each pair of n nodes one edge, so building the graph takes O(n^2) work. Timsort takes O(n log n), but running prim from 
before takes O(n^2 log n). This dominates, so the total work is O(n^2 log n).
