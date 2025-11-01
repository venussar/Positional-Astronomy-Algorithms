# Positional Astronomy Algorithms

This repository contains fundamental algorithms and computational exercises for **Positional Astronomy** and **Geodesy** (Earth measurements). The focus is on implementing mathematical formulas to solve positional problems.

---

## 📜 Contents

1.  [Great-Circle Distance Calculation](#1-great-circle-distance-calculation)
2.  [**Satellite Ground Track Analysis and Geocentric Conversion**](#2-satellite-ground-track-analysis-and-geocentric-conversion)

---

### 1. Great-Circle Distance Calculation

This project involves developing and testing an algorithm to find the **minimum distance between two points on the Earth's surface** (the Great-Circle Distance).

* **Algorithm:** The implementation uses spherical trigonometry, specifically the **Spherical Law of Cosines** , adapted to handle edge cases related to longitude (crossing the International Date Line/Anti-meridian).
* **Validation:** The code is tested with various pairs of points and the results are compared against external sources (e.g., Google Earth or specialized calculators).

---

### 2. Satellite Ground Track Analysis and Geocentric Conversion (NEW)

This project analyzes the ground track of a calibration satellite over six terrestrial stations, focusing on advanced geodetic calculations and coordinate transformations.

* **Data Handling:** Construct and process a table containing the geodetic coordinates (latitude, longitude, altitude) of six terrestrial stations (A, B, C, D, E, F).
* **Coordinate Transformation:** Implement a Python function to convert the geodetic coordinates (assuming a reference ellipsoid like **WGS84**) into **geocentric coordinates** (ECEF).
* **Distance Matrix:** Calculate the distance between every pair of stations using **spherical trigonometry theorems** and generate the resulting $n \times n$ distance matrix.
* **Great Circle Path Analysis:** For each trajectory between two stations:
    * **Equator/Meridian Crossing:** Determine if the path crosses the terrestrial Equator and/o the Greenwich Meridian.
    * **Initial and Final Course (Rumbo):** Calculate the **initial bearing** (rumbo inicial) and the **final bearing** (rumbo final)  for that trajectory, which defines the direction of travel along the great circle path.



* ### Skills Demonstrated
Implementation of spherical trigonometry formulas in code.

Handling geographical coordinate systems (latitude and longitude).

Computational problem-solving in Geodesy and Positional Astronomy.

Logic for handling edge cases (e.g., crossing the anti-meridian).

###Author
Developed by [Carolina Andrea Rodas Castañeda] as part of the Positional Astronomy coursework.
