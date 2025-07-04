# Matrices - Beginner Session Outline

## 1. Definition and Notation of Matrices

### What is a Matrix?

* A matrix is a rectangular array of numbers arranged in rows and columns.
* Notation: Capital letters like **A**, **B**, **C** are used to denote matrices.

### Matrix Dimensions:

* A matrix with **m** rows and **n** columns is called an **m × n** matrix.
* Example:

  ```
  A = \begin{bmatrix}
  1 & 2 & 3 \\
  4 & 5 & 6
  \end{bmatrix}
  ```

  This is a 2 × 3 matrix.

---

## 2. Types of Matrices

* **Row Matrix**: Only one row (e.g., `1 × n`)
* **Column Matrix**: Only one column (e.g., `m × 1`)
* **Square Matrix**: Number of rows = number of columns (e.g., 2 × 2, 3 × 3)
* **Zero Matrix**: All elements are zero
* **Identity Matrix (I)**:

  * A square matrix with 1s on the diagonal and 0s elsewhere
  * Example (3 × 3):

    ```
    I = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}
    ```
* **Diagonal Matrix**: A square matrix where all off-diagonal elements are 0

  * Example:

    ```
    D = \begin{bmatrix} 2 & 0 & 0 \\ 0 & 5 & 0 \\ 0 & 0 & -1 \end{bmatrix}
    ```

---

## 3. Basic Matrix Operations

### Matrix Addition/Subtraction:

* Only possible if both matrices have the **same dimensions**
* Performed element-wise
* Example:

  ```
  A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix},
  B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}
  A + B = \begin{bmatrix} 6 & 8 \\ 10 & 12 \end{bmatrix}
  ```

### Scalar Multiplication:

* Multiply each element by a constant
* Example: 2 × A

---

## 4. Matrix Multiplication

### Conditions:

* Number of **columns** in the first matrix = number of **rows** in the second matrix
* Result is a matrix with dimensions: (rows of first) × (columns of second)

### Example:

```
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}
B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}
A × B = \begin{bmatrix} (1×5 + 2×7) & (1×6 + 2×8) \\ (3×5 + 4×7) & (3×6 + 4×8) \end{bmatrix}
      = \begin{bmatrix} 19 & 22 \\ 43 & 50 \end{bmatrix}
```

---

## 5. Determinants (Square Matrices)

### Definition:

* A scalar value that can be computed from a square matrix

### Determinant of 2 × 2:

```
A = \begin{bmatrix} a & b \\ c & d \end{bmatrix},
|A| = ad - bc
```

### Determinant of 3 × 3 (Rule of Sarrus):

```
A = \begin{bmatrix} a & b & c \\ d & e & f \\ g & h & i \end{bmatrix}
|A| = aei + bfg + cdh - ceg - bdi - afh
```

### Applications:

* Used to determine invertibility
* Useful in solving linear systems (Cramer's Rule)

---

## 6. Inverse of a Matrix

### Conditions:

* Only square matrices that are **non-singular** (determinant ≠ 0) have an inverse

### Notation:

* Inverse of matrix **A** is denoted by **A⁻¹**

### 2 × 2 Matrix Inverse:

```
A = \begin{bmatrix} a & b \\ c & d \end{bmatrix},
A⁻¹ = \frac{1}{ad - bc} \begin{bmatrix} d & -b \\ -c & a \end{bmatrix}
```

### Properties:

* A × A⁻¹ = I

---

Let me know if you'd like to include example problems, exercises, or matrix visualizations!
