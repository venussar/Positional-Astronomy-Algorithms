# Positional Astronomy Algorithms

This repository contains fundamental algorithms and computational exercises for **Positional Astronomy** and **Geodesy** (Earth measurements). The focus is on implementing mathematical formulas to solve positional problems.

---

## 📜 Contents

1.  [Great-Circle Distance Calculation](#1-great-circle-distance-calculation)

---

### 1. Great-Circle Distance Calculation

This project involves developing and testing an algorithm to find the **minimum distance between two points on the Earth's surface** (the Great-Circle Distance).

* **Algorithm:** The implementation uses spherical trigonometry, specifically the **Spherical Law of Cosines** , adapted to handle edge cases related to longitude (crossing the International Date Line/Anti-meridian).
* **Implementation:** The algorithm is implemented as a Python function that takes the latitude and longitude of two points (in degrees) and returns the distance in kilometers, assuming the Earth's radius ($R$) is $6371.0\,\text{KM}$.
* **Validation:** The code is tested with various pairs of points and the results are compared against external sources (e.g., Google Earth or specialized calculators).

*  Skills Demonstrated
Implementation of spherical trigonometry formulas in code.

Handling geographical coordinate systems (latitude and longitude).

Computational problem-solving in Geodesy and Positional Astronomy.

Logic for handling edge cases (e.g., crossing the anti-meridian).

Author
Developed by [Carolina Andrea Rodas Castañeda] as part of the Positional Astronomy coursework.
