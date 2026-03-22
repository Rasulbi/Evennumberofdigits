# Evennumberofdigits
# 📊 Find Numbers with Even Number of Digits

## 🧩 Problem Statement

Given an array `nums` of integers, return how many of them contain an **even number of digits**.

---

## 📥 Examples

### Example 1

```
Input: nums = [12, 345, 2, 6, 7896]
Output: 2
```

**Explanation:**

* 12 → 2 digits ✅
* 345 → 3 digits ❌
* 2 → 1 digit ❌
* 6 → 1 digit ❌
* 7896 → 4 digits ✅
  ➡️ Total = 2

---

### Example 2

```
Input: nums = [555, 901, 482, 1771]
Output: 1
```

**Explanation:**

* Only 1771 has even number of digits

---

## 🎯 Approach

### Step-by-Step

1. Initialize a counter variable.
2. Loop through each number in the array.
3. Count the number of digits in each number.
4. Check if the digit count is even.
5. If yes, increment the counter.
6. Return the final count.

---



## ⏱️ Time Complexity

* **O(n × d)**

  * `n` = number of elements
  * `d` = number of digits

---

## 📌 Key Points

* Number `0` has **1 digit**
* Avoid string conversion for better performance (in interviews)
* Mathematical approach is preferred

---

## 🚀 Problem Source

* LeetCode Problem #1295
* "Find Numbers with Even Number of Digits"

---

## 🧪 Practice Ideas

* Try with negative numbers
* Optimize using `log10`
* Modify to count odd digit numbers

---

✨ Happy Coding!
