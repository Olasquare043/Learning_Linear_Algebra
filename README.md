# 📘 Matrix Multiplication with NumPy
This repository contains a Jupyter Notebook that demonstrates **matrix operations** as part of the Gen AI Fellowship Programme's **Linear Algebra class**.  
The focus is on solving a matrix multiplication task both **manually (step-by-step)** and **using NumPy in Python**.

---

### 📝 Task Description
We are given two matrices:
A =
\begin{bmatrix}
2 & -1 & 3 \\
0 & 4 & 1
\end{bmatrix},

B =
\begin{bmatrix}
1 & 2 \\
-2 & 0 \\
5 & 3
\end{bmatrix}


`We need to:`
1. Identify the number of rows and columns in each matrix.  
2. Determine whether the matrices can be multiplied (AB, BA, or both).  
3. If multiplication is defined, compute the resulting matrix using:  
   - **A. NumPy computation**  
   - **B. Manual step-by-step computation**

---
### 🚀 Solution Overview
`1. Matrix Dimensions`
- **Matrix A** → 2 × 3  
- **Matrix B** → 3 × 2  

`2. Multiplication Feasibility`
- Both **AB** and **BA** are valid.  
- AB will result in a **2 × 2** matrix.  
- BA will result in a **3 × 3** matrix.  

`3. Results`
- **AB (Manual & NumPy)**  
AB =
\begin{bmatrix}
19 & 13 \\
-3 & 3
\end{bmatrix}

- **BA (NumPy)**  
BA =
\begin{bmatrix}
2 & 7 & 5 \\
-4 & 2 & -6 \\
10 & 7 & 18
\end{bmatrix}

---
### 📂 Repository Structure
├── Matric_multiplication_with_numpy.ipynb

├── README.md

---
### ⚙️ Installation & Setup
Clone the repository and install dependencies:

- git clone https://github.com/Olasquare043/Learning_Linear_Algebra.git
- cd Learning_Linear_Algebra
- pip install numpy

---
### ▶️ Running the Notebook
Launch Jupyter Notebook:
- jupyter notebook Matric_multiplication_with_numpy.ipynb

`Run the cells to see:`
- NumPy computation results
- Manual verification of matrix multiplication

### 🎯 Key Learning Outcomes
- Understand matrix dimensions and multiplication rules.
- Differentiate between AB and BA multiplication.
- Apply both manual computation and NumPy automation.
- Build intuition for linear algebra concepts essential in AI/ML.

### 📌 Author
This notebook was developed as part of the Gen AI Fellowship Programme (Linear Algebra Module).

👤 Saheed Olayinka Olayemi
🔗 https://github.com/Olasquare043