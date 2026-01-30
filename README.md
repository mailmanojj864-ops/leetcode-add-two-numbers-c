# leetcode-add-two-numbers-c
Clean and optimized C solution for LeetCode Problem #2 – Add Two Numbers using singly linked lists.

# LeetCode #2 – Add Two Numbers (C Implementation)

🚀 **Clean, efficient, and fully accepted C solution for LeetCode Problem #2: Add Two Numbers.**

This repository contains a professional implementation using **singly linked lists**, handling digit-by-digit addition with carry propagation.

---

## 📌 Problem Summary

You are given two non-empty linked lists representing two non-negative integers.  
The digits are stored in **reverse order**, and each node contains a **single digit**.

Add the two numbers and return the sum as a linked list.

### Example
Input:
l1 = [2,4,3]
l2 = [5,6,4]

Output:
[7,0,8]

Explanation:
342 + 465 = 807


---

## 🧠 Approach

- Traverse both linked lists simultaneously
- Add corresponding digits along with carry
- Create new nodes dynamically for the result list
- Continue until both lists and carry are exhausted

---

## 💡 Algorithm

1. Initialize `carry = 0`
2. Create a dummy node to simplify result list creation
3. While either list exists or carry remains:
   - Add node values and carry
   - Store digit using modulo operation
   - Update carry using division
4. Return the final linked list

| Metric | Complexity       |
| ------ | ---------------- |
| Time   | **O(max(n, m))** |
| Space  | **O(max(n, m))** |

Where:

n = length of first linked list

m = length of second linked list


