# Singular Value Decomposition:

### The Singular Value Decomposition (SVD) of a matrix is a factorization of that matrix into three matrices

Singular Value Decomposition (SVD) is performed on the train_data to decompose it into U (left singular vectors), S (singular values), and VT (right singular vectors).

Dimensionality is reduced by selecting the first k components (U_k, S_k, VT_k).

Synthetic data is generated using the reduced SVD components.

**MinMaxScaler** is instantiated and fitted to train_data to scale the synthetic data back to its original range.

The shape of synthetic_data is printed and then saved to a CSV file named synthetic_data.csv.

If train_data is a DataFrame, synthetic_data is converted to a DataFrame (synthetic_df) with appropriate column names; otherwise, it's saved as is.

Simple example to practice(to not overcomplicate it):
import numpy as np

### Example matrix A
```python
A = np.array([[1, 0, 0],
              [0, 2, 0],
              [0, 0, 3]])

#Perform SVD
U, S, VT = np.linalg.svd(A, full_matrices=True)

#U, S, VT represent matrices such that A = U @ np.diag(S) @ VT
```
