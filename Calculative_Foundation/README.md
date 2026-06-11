# 📘 Linear Algebra for Data Science Project

## 🎯 Project Overview

This project demonstrates the application of Linear Algebra concepts in Data Science using a Student Performance Dataset.

The dataset contains scores of students in five subjects:

* Physics
* Chemistry
* Biology
* Geography
* Arts

Using these scores, various vector operations, matrix operations, decompositions, and dimensionality reduction techniques are implemented.

---

# 📂 Dataset Information

### Dataset Features

| Column      | Description               |
| ----------- | ------------------------- |
| ID          | Student ID                |
| Physics     | Physics Score             |
| Chemistry   | Chemistry Score           |
| Biology     | Biology Score             |
| Geography   | Geography Score           |
| Arts        | Arts Score                |
| Total_Score | Sum of all subject scores |
| Performance | High / Low Performance    |

### Dataset Shape

```text
150 Students × 8 Columns
```

---

# 🛠️ Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.decomposition import PCA
from sklearn.discriminant_analysis import LinearDiscriminantAnalysis as LDA
from sklearn.preprocessing import LabelEncoder
from scipy.linalg import lu
```

---

# 📘 Part A: Vector & Matrix Fundamentals

## 1️⃣ Vector Representation

Each student's subject scores are represented as a vector.

Example:

```text
Student = [Physics, Chemistry, Biology, Geography, Arts]
```

### Operations Performed

✅ Create student vectors

✅ Compare student performance using vectors

---

## 2️⃣ Vector Norms

Computed:

* Norm-1 (Manhattan Norm)
* Norm-2 (Euclidean Norm)

Purpose:

* Measure vector magnitude
* Compare score distributions

---

## 3️⃣ Dot Product

Calculated the dot product between two student vectors.

Purpose:

* Measure similarity between students

---

## 4️⃣ Angle Between Vectors

Calculated angle using cosine similarity.

Purpose:

* Determine how similar two students are academically

---

## 5️⃣ Cross Product

Created 3D vectors using:

* Physics
* Chemistry
* Biology

Purpose:

* Demonstrate vector orthogonality

---

## 6️⃣ Vector Projection

Projected Student S001 onto Student S002.

Purpose:

* Measure directional contribution

---

# 📘 Part B: Matrix Operations

## 7️⃣ Student × Subject Matrix

Created matrix:

```text
Rows → Students
Columns → Subjects
```

Shape:

```text
150 × 5
```

---

## 8️⃣ Matrix Addition & Multiplication

Performed:

✅ Matrix Addition

✅ Matrix Multiplication

Purpose:

* Understand matrix transformations

---

## 9️⃣ Matrix Transpose

Converted:

```text
150 × 5
```

to

```text
5 × 150
```

Purpose:

* Covariance calculations
* Matrix manipulation

---

## 🔟 Determinant & Inverse

Computed:

✅ Determinant

✅ Inverse Matrix (for square matrix)

Purpose:

* Check matrix invertibility

---

# 📘 Part C: Linear Transformation & Geometry

## 1️⃣1️⃣ Line, Plane & Hyperplane

Represented data in:

### 📍 1D Line

Physics Scores

### 📍 2D Plane

Physics + Chemistry

### 📍 5D Hyperplane

All Subject Scores

---

## 1️⃣2️⃣ Dimensionality Representation

Visualized:

* 2D Data
* 3D Data
* 5D Data

Created scatter plot:

```text
Physics vs Chemistry
```

Purpose:

* Understand geometric representation of data

---

# 📘 Part D: Matrix Decomposition

## 1️⃣3️⃣ Eigenvalues & Eigenvectors

Computed eigenvalues and eigenvectors of covariance matrix.

Purpose:

* Identify principal directions of variation

---

## 1️⃣4️⃣ LU Decomposition

Decomposed matrix into:

```text
A = LU
```

Where:

* L → Lower Triangular Matrix
* U → Upper Triangular Matrix

Purpose:

* Efficient matrix computation

---

## 1️⃣5️⃣ Singular Value Decomposition (SVD)

Performed:

```text
A = UΣVᵀ
```

Generated:

* Singular Values
* U Matrix
* Vᵀ Matrix

Created bar chart of singular values.

Purpose:

* Feature extraction
* Dimensionality reduction

---

# 📘 Part E: Dimensionality Reduction

## 1️⃣6️⃣ Principal Component Analysis (PCA)

Reduced:

```text
5 Dimensions → 2 Dimensions
```

Computed:

* Principal Components
* Explained Variance Ratio

Created PCA scatter plot.

Purpose:

* Reduce dimensionality
* Preserve important information

---

## 1️⃣7️⃣ Linear Discriminant Analysis (LDA)

Classified students into:

🟢 High Performance

🔴 Low Performance

Reduced:

```text
5 Dimensions → 1 Dimension
```

Created LDA visualization.

Purpose:

* Maximize class separation
* Improve classification

---

# 📊 Visualizations Included

✅ Physics vs Chemistry Scatter Plot

✅ Singular Value Bar Chart

✅ PCA Scatter Plot

✅ LDA Classification Plot

---

# 🎯 Learning Outcomes

Through this project, the following concepts were implemented:

✅ Vector Representation

✅ Vector Norms

✅ Dot Product

✅ Cross Product

✅ Projection

✅ Matrix Operations

✅ Determinant & Inverse

✅ Linear Transformations

✅ Eigenvalues & Eigenvectors

✅ LU Decomposition

✅ SVD

✅ PCA

✅ LDA

---

# 🎓 Conclusion

This project demonstrates how Linear Algebra forms the mathematical foundation of Data Science and Machine Learning. Concepts such as vectors, matrices, decompositions, PCA, and LDA help analyze, transform, visualize, and classify multidimensional student performance data effectively.
