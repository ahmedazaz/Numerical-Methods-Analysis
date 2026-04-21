# Numerical Methods Analysis: Precision and Errors

This repository contains a collection of numerical analysis experiments conducted as part of my **Master's in Computer Engineering** at Bilecik Şeyh Edebali University. The project focuses on practical implementations of mathematical concepts and their numerical stability in Python.

## 🔬 Project Overview

Computing is inherently limited by floating-point precision. This project explores how different algorithms behave under various conditions, specifically analyzing the trade-off between mathematical accuracy and computational limits.

### Topics Covered:

* **Numerical Differentiation:** Implementation of Forward, Backward, and Centered difference methods. Analysis of the balance between **Truncation Error** and **Round-off Error** (the "V-curve" phenomenon).
* **Taylor Series Convergence:** Approximating $e^x$ and observing how the relative error decreases as the degree of the polynomial increases.
* **Numerical Stability (Underflow):** Handling extremely small probabilities using **Log-domain** summation to prevent arithmetic underflow.
* **Variance Calculation Stability:** Comparing naive vs. stable (two-pass) algorithms to avoid **Catastrophic Cancellation** when handling large datasets.

## 🛠 Tools & Libraries

* **Python 3**
* **NumPy:** For advanced array manipulation and mathematical stability.
* **Matplotlib:** For visualizing error convergence and stability analysis.

## 📊 Key Findings

Through these experiments, we identified that the **Centered Difference** method provides higher accuracy ($O(h^2)$) compared to Forward/Backward methods, but remains vulnerable to precision loss at extremely small step sizes ($h < 10^{-12}$).

---
Developed by **Ahmed Azaz**
