# Multivariable Calculus Project — BSDS-IV (Spring 2025)

**Group Members:**  
- **232542** Abdul Wahab  
- **232546** Arhum Ahmad  
- **232550** Abdullah Hassan  

---

## 🌟 Introduction
This repository presents a **comprehensive, all-in-one Python implementation** of our **Multivariable Calculus Project**.  
The project is encapsulated in a single Python script — `multivariable_calculus.py` — that integrates **symbolic mathematics**, **numerical computation**, **3D visualization**, and **data exporting** for **three real-world multivariable optimization problems**.  

Our goal was to create a **reproducible, structured, and professional** solution that closely aligns with the mathematical rigor of our original report while making it **easy to run, understand, and extend**.

The **original report** is included in the `data/` folder for reference.

---

## 🎯 Project Scope

| **Question** | **Objective** | **Key Mathematical Tools** | **Expected Output** |
|--------------|--------------|----------------------------|---------------------|
| **Q1: Latency Function Analysis** | Minimize latency between two servers | Partial derivatives, critical points, boundary analysis, exhaustive search | CSV file with minima, 3D surface plot |
| **Q2: Cobb–Douglas Optimization** | Maximize production under a cost constraint | Lagrange multipliers, constrained optimization | TXT file with optimal values, 3D surface plot |
| **Q3: Profit Optimization** | Maximize profit for producing DVD players & recorders | Partial derivatives, Hessian definiteness check | TXT file with max profit, 3D surface plot |

---

## 📚 Detailed Problem Descriptions

### **1️⃣ Latency Function Analysis**
- **Function:** A two-variable latency model representing delays between two servers.  
- **Process:**  
  1. Define \( L(x, y) \).  
  2. Compute \( \frac{\partial L}{\partial x} \) and \( \frac{\partial L}{\partial y} \).  
  3. Solve for critical points.  
  4. Perform **boundary and exhaustive search**.  
  5. Plot the function in 3D.  
- **Outputs:**  
  - `outputs/results/q1_results.csv` — detailed results table.  
  - `outputs/figures/q1_surface.png` — 3D surface plot.

---

### **2️⃣ Cobb–Douglas Production Optimization**
- **Function:** \( P(x, y) = A x^a y^b \) with a linear cost constraint.  
- **Process:**  
  1. Define the Cobb–Douglas production function.  
  2. Form the **Lagrangian**.  
  3. Apply **Lagrange multipliers**.  
  4. Solve for optimal \( x, y \) and calculate max production.  
  5. Plot the production surface.  
- **Outputs:**  
  - `outputs/results/q2_results.txt` — optimal inputs & production.  
  - `outputs/figures/q2_surface.png` — 3D surface plot.

---

### **3️⃣ Profit Optimization**
- **Function:** Profit from producing DVD players and recorders.  
- **Process:**  
  1. Define \( \pi(x, y) \).  
  2. Compute partial derivatives.  
  3. Solve for critical points.  
  4. Use the **Hessian matrix** to confirm maxima.  
  5. Plot the profit surface.  
- **Outputs:**  
  - `outputs/results/q3_results.txt` — max profit & production values.  
  - `outputs/figures/q3_surface.png` — 3D surface plot.

---

## 🛠 Key Features & Behaviours

| **Feature** | **Description** |
|-------------|-----------------|
| **All-in-One Execution** | Running `multivariable_calculus.py` executes all three problems sequentially. |
| **Symbolic Calculations** | Exact results using `sympy` for derivatives, solving equations, and Hessian checks. |
| **Numerical Validation** | Boundary checks and grid evaluations using `numpy`. |
| **High-Quality Plots** | 3D surface plots with labeled axes and saved as PNG. |
| **Automated Data Saving** | Structured output folders for CSV/TXT results and figures. |
| **Clear Console Output** | Key results printed in human-readable format. |

---

