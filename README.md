# Python for Computational Linear Algebra

## Python packages

- [`numpy`](https://numpy.org) (numerical linear algebra)
- [`sympy`](https://www.sympy.org/en/index.html) (symbolic & computational linear algebra)

## Basic method

### `sympy` library

|Method | Usage |
|--|--|
|`.rref()` | Gauss-Jordan eliminations|
|`.rank()` | Matrix rank |
|`.col_insert()`| Insert columns |
|`.row_insert()`| Insert rows |
|`.det()`| Matrix determinant |
|`.eigenvals()` | Matrix eigenvalues |
|`.eigenvects()` | Matrix eigenvactors |
|`shape()`| Matrix shape |
|`@`| Matrix multiplication |

### `numpy.linalg` library

|Method | Usage |
|--|--|
|`.matrix_power(a,n)`| Matrix power |
| `.eig(a)`| eigenvalues & eigenvetctors|
|`.eigvals(a)` |eigenvalues only |
|`.det(a)` | Matrix determonant |
|`.matrix_rank()`| Matrix rank |
|`.solve(a, b)` | Solve a linear matrix equation, or system of linear scalar equations|
|`.inv(a)`|  the inverse of a matrix |
|`.norm()`| Matrix/vector norm |
