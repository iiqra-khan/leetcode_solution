# LeetCode Solutions

This repository contains my solutions to problems from [LeetCode](https://leetcode.com/), written in Python. It serves as my coding practice log and a personal reference for algorithms and data structures.

## 🗂 Folder Structure
leetcode-solutions/
├── easy/
│ └── 1_two_sum.py
├── medium/
│ └── 3_longest_substring.py
├── hard/
│ └── 10_regular_expression_matching.py

## 📌 Categories

- `easy/` – Easier problems, good for warm-up
- `medium/` – Intermediate-level problems with some complexity
- `hard/` – Challenging problems requiring deep thinking and optimization

## ✅ Problem Format

Each Python file includes:

- Problem name
- LeetCode link
- Difficulty
- My solution

### Example: `easy/1_two_sum.py`
```python
# Problem: Two Sum
# Link: https://leetcode.com/problems/two-sum/
# Difficulty: Easy

class Solution:
    def twoSum(self, nums, target):
        prev_val = {}
        for i, val in enumerate(nums):
            if target - val in prev_val:
                return [i, prev_val[target - val]]
            prev_val[val] = i

| Difficulty | Count |
| ---------- | ----- |
| Easy       | ✅ 1   |
| Medium     | ✅ -   |
| Hard       | ✅ -  |
