# 📊 Calculative Foundation Project

## Linear Algebra in Data Science, AI/ML & Engineering

---

## 📌 Project Overview

This project focuses on applying fundamental **Linear Algebra concepts** to analyze and transform a dataset of students' academic performance. The goal is to understand how mathematical techniques like vectors, matrices, decompositions, and dimensionality reduction are used in real-world data analysis and machine learning.

---

## 🎯 Objective

The objective of this project is to:

* Represent and manipulate data using **vectors and matrices**
* Perform operations like **norms, dot product, cross product, and projection**
* Apply **matrix transformations and decompositions**
* Use **dimensionality reduction techniques (PCA & LDA)**
* Extract meaningful insights from student performance data

---

## 📊 Dataset Description

The dataset consists of **50 students** and their scores in four subjects:

* Math
* Science
* English
* Computer

Each student is represented as a **vector in 4-dimensional space**, where each dimension corresponds to a subject.

---

## 🧮 Part A: Vector & Matrix Fundamentals

### 🔹 Vector Representation

Each student’s marks are represented as a vector:

* This allows mathematical operations like distance, similarity, and projections.

### 🔹 Norms

* **L1 Norm**: Sum of absolute values → measures total magnitude
* **L2 Norm**: Euclidean length → measures actual distance

### 🔹 Dot Product

* Measures similarity between two students
* Higher value → more similar performance

### 🔹 Angle Between Vectors

* Small angle → similar students
* Large angle → different students

### 🔹 Cross Product

* Used in 3D to find a perpendicular vector

### 🔹 Vector Projection

* Shows how much one student’s performance aligns with another

---

## 🧱 Part B: Matrix Operations

### 🔹 Matrix Formation

* Dataset is represented as a matrix (Students × Subjects)

### 🔹 Matrix Addition

* Element-wise addition of values

### 🔹 Matrix Multiplication

* Used to find relationships between students

### 🔹 Transpose

* Converts rows into columns

### 🔹 Determinant

* Determines if a matrix is invertible

### 🔹 Inverse

* Used to solve matrix equations

---

## 📐 Part C: Linear Transformations & Geometry

### 🔹 Line (1D)

* Represents single feature data

### 🔹 Plane (2D)

* Represents data with two features

### 🔹 Hyperplane (nD)

* Represents multi-dimensional data

### 🔹 Dimensional Growth

* 2D → 3D → nD as features increase
* Students exist in **4D space** in this dataset

---

## 🔍 Part D: Eigenvalues & Decomposition

### 🔹 Eigenvalues & Eigenvectors

* Eigenvectors → direction of data
* Eigenvalues → importance of direction

### 🔹 Covariance Matrix

* Shows relationships between subjects
* Helps understand correlation

### 🔹 LU Decomposition

* Breaks matrix into lower and upper matrices

### 🔹 Singular Value Decomposition (SVD)

* Decomposes matrix into simpler components
* Used in data compression and noise reduction

---

## 📉 Part E: Dimensionality Reduction

### 🔹 Principal Component Analysis (PCA)

* Reduces dataset from 4 dimensions to 2
* Retains maximum variance
* Helps in visualization and simplification

### 🔹 Linear Discriminant Analysis (LDA)

* Classifies students into:

  * Above Average
  * Below Average
* Uses data separation techniques

---

## 📌 Key Insights

* Students with similar scores have **higher similarity (dot product)**
* Some subjects show **positive correlation**
* PCA helps reduce complexity while keeping important information
* Eigenvalues reveal **important patterns in data**
* LDA helps in **classification and decision-making**

---

## 🎯 Conclusion

This project demonstrates how linear algebra plays a crucial role in data analysis and machine learning. By representing data as vectors and matrices, we can perform advanced computations to uncover patterns, relationships, and insights. Techniques like PCA and LDA help simplify complex datasets and enable better interpretation and classification of data.

---

## 🚀 Learning Outcomes

* Strong understanding of **vector and matrix operations**
* Practical knowledge of **linear algebra in real-world datasets**
* Ability to apply **PCA, LDA, and decomposition techniques**
* Foundation for **machine learning and data science applications**

---

## 📌 Tools Used

* Python
* NumPy
* Pandas
* Matplotlib

---

## 👨‍💻 Author

Aryan Dhanwani

---

## ⭐ Final Note

This project bridges the gap between theoretical linear algebra concepts and their real-world applications in **Data Science, AI/ML, and Engineering**, providing a strong analytical foundation.

---
