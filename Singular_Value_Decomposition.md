# Singular Value Decomposition
### Geometric Perspective

 - If you're transforming a matrix then you can choose to do so by multiplying matrix A by matrix B. 
 - The SVD of matrix B will separate it out into three different matrices where B = U * S * __V__ transpose. U and V only perform rotations whereas S performs scaling. So in SVD, you rotate you original matrix until it is aligned with the main axis using U, then scale / stretch it along this axis using S, and then rotate it. 
   - U = rotate
   - S = stretch
   - V = rotate
