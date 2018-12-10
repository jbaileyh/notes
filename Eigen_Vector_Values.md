# Eigen Vectors / Values
### TB1B

- Eigenvectors of a transformation are the vectors in a space that don't change 'direction' when a vector undergoes transformation. 
- The Eigenvalue is the amoun that the eigenvectors are stretched or squished during the transformation.
- In multiple dimiensions, when undergoing geometric transformations the eigen vector is essentially the axis of rotation.
- It's often easier to compute rotations around an axis than it is to do a full multi-dimensional transformation. 
- Matrix A * Vector V = Lambda * Vector V
  - _Matrix multiplication = Scalar multiplication_
  - V is the eigenvector.
  - Lambda is a number and the corresponding Eigenvalue
  - The matrix vector product (A*V) gives the same result as scaling V by Lambda. 
  - Find values for V and Lambda that make the expression above true. 

Instead of scaling by the Lambda:

- Turn the scalar into an identity matrix I (diagonal 1's all else 0's)
- Then do Lambda * I * Vector V
- So it becomes Matrix A * Vector V = Lambda * Matrix I * Vector V
- Subtract off right hand side and factor out Vector V. 
- So find the vector V that when multiplied by (Matrix X - Lambda * Matrix I) * V the result is 0
  - To do this, manipulate the value of Lambda, until the determinant of the matrix is equal to 0. 
  - See determinant notes. 


- 2D Transformation doesn't have to have eigenvectors (e.g. 90 degree rotation)
