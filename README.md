# 📉 Real Root-Finding Methods in MATLAB

This project applies **numerical methods** to find real roots of equations using both the **Bisection Method** and **Newton's Method** in MATLAB. It includes performance comparisons and visualizations of convergence speed across tolerances.

## 🧠 Methods Implemented

- **Bisection Method**  
  Applies the Intermediate Value Theorem to iteratively narrow down an interval containing a root.

- **Newton's Method**  
  Uses derivatives to iteratively estimate root convergence via tangent lines.

## 📊 Features

- Comparison of convergence speed between Bisection and Newton’s methods
- Visualization of:
  - Cooling rate vs bar length (from root calculations)
  - Iterations required vs tolerance (log-scale)
- Modular MATLAB functions with adjustable tolerances and ranges

## 📈 Key Concepts

- Root-finding for one-variable functions
- Convergence behavior and iteration count analysis
- MATLAB function handles (`@`), plotting, and iterative methods

## 🚀 How to Run

1. Open `Project2.m` in MATLAB
2. Ensure any function files (`Bis`, `Newt`) are in the same folder
3. Run:

```matlab
Project2
