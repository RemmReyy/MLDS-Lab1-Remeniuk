# MLDS-Lab1-Remeniuk
**Laboratory Work #1** – Python, NumPy, Pandas & Matplotlib  
**Score:** 12 / 12 ✏️  
**Student:** Remeniuk  

![Python](https://img.shields.io/badge/python-3.11-blue)  
![NumPy](https://img.shields.io/badge/numpy-1.26-orange)  
![Pandas](https://img.shields.io/badge/pandas-2.2-green)  
![Matplotlib](https://img.shields.io/badge/matplotlib-3.9-purple)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/MLDS-Lab1-Remeniuk/blob/main/Task1_basic_MLDS_Remeniuk.ipynb)

---

## 📌 What’s inside?
12 fully solved tasks (no loops, fully vectorised):

| # | Task | One-liner |
|---|------|-----------|
| 1 | Palindrome check | `s == s[::-1]` |
| 2 | Quadratic equation | Handles `a=0`, returns 0–2 roots |
| 3 | Merge two sorted lists | `sorted(a+b)` |
| 4 | MergeSort (recursive) | O(n log n) with custom `merge` |
| 6 | Are three arrays equal? | `np.array_equal` |
| 7 | Row → column vector | `reshape(-1, 1)` |
| 8 | Main diagonal | `np.diagonal(X)` |
| 9 | Anti-diagonal | `np.diagonal(np.fliplr(X))` |
|10 | Titanic: men vs women | `value_counts()` |
|11 | Age stats (overall + by sex) | `groupby('Sex')['Age'].agg(['mean','min','max'])` |
|12 | 5 trigonometric plots | Fully styled with legend, grid, labels |

---

## 🚀 Quick Start

```bash
git clone https://github.com/YOUR_USERNAME/MLDS-Lab1-Remeniuk.git
cd MLDS-Lab1-Remeniuk
jupyter notebook Task1_basic_MLDS_Remeniuk.ipynb
