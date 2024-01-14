# Abhiraj Pratap Singh
---

# UPVOTE IT.....

---



# Intuition
<!-- Describe your first thoughts on how to solve this problem. -->
- The problem requires reversing a string, which means swapping the characters from the start and end positions until you reach the middle of the string.

---

![Screenshot (47).png](https://assets.leetcode.com/users/images/371eb601-5dd8-4608-9e47-1d70c02b548e_1705252810.9153218.png)

---


# Approach
<!-- Describe your approach to solving the problem. -->
1. Initialize two pointers, start at the beginning (0) and end at the end of the string (s.size() - 1).
2. Use a while loop that continues as long as start is less than end.
3. Inside the loop, swap the characters at positions start and end.
4. Increment start and decrement end after each swap.
5. Repeat steps 3-4 until start is greater than or equal to end.
6. The string is now reversed.


---


# Complexity
- Time complexity:
<!-- Add your time complexity here, e.g. $$O(n)$$ -->

- **Time complexity: O(n),** where n is the length of the string.
    - The loop runs up to the middle of the string, performing       constant time operations for each swap.


---


- Space complexity:
<!-- Add your space complexity here, e.g. $$O(n)$$ -->

- **Space complexity: O(1),** as the algorithm uses constant extra space regardless of the length of the input string.


---

