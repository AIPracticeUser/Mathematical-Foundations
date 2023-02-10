# Mathematical Foundations of Machine Learning
## Essential Linear Algebra and Calculus Hands-On in NumPy, TensorFlow, and PyTorch
## Course Instructor: Dr Jon Krohn
## website : https://www.udemy.com/course/machine-learning-data-science-foundations-masterclass/

--------------------------------------------------------
# Linear Algebra
## "Solving for Unknowns within the systems of Linear Equations"
![image](https://user-images.githubusercontent.com/100339175/217941391-052f4bac-5f0b-4329-a7e1-1329c3b6450c.png)
![image](https://user-images.githubusercontent.com/100339175/217941516-5030145b-f7e2-4ee7-82c0-63e877873eca.png)

https://github.com/AIPracticeUser/Mathematical-Foundations/blob/09b45bd0f4f86125ff6c01cc42f14cb2c75e36a5/Maths_1_(Linear_Algebra).ipynb
--------------------------------------------------------

# Tensors
## "ML generalization of vectors and matrices to any number of dimensions"
![image](https://user-images.githubusercontent.com/100339175/217940322-937024fa-d00b-461f-9cd9-6e9cda6dbaa6.png)
## Scalars
- No dimensions
- Single number
- Denoted in lowercase, italics, e.g.: x
- Should be typed like all other tensors: eg, int, float32

## Vectors
- One-dimensional array of numbers
- Denoted in lowercase, italics, bold, eg: x
- Arrange in an order, so element can be accessed by its index
  - example [x1 x2] = [12 4]
- Represent a point in space
  -  Vector of length two represents location in 2D matrix
  -  Length of three represents location in 3D cube
  -  Length of n represents location in n-dimensional tensor
-  ![image](https://user-images.githubusercontent.com/100339175/217951812-6542383e-4435-4eb9-a6ac-2aed624109cb.png)
  - Why a need to transpose vectors or matrices ?
  - "These ML models are nothing but a series of linear transformation of matrices (leave aside non-linear activation at the moment). Thus, you’ll need to match the matrix dimensions for computation, and that’s really the only reason you transpose matrices"
- ![image](https://user-images.githubusercontent.com/100339175/218033675-8c88c52a-eac0-4f39-a406-296e49798be7.png)
- ![image](https://user-images.githubusercontent.com/100339175/218036041-479944b8-40c7-4ffa-94e4-52e5da06d757.png)
  -  Measures simple (Euclidean) distance from origin (example point 0,0)
  -  Most common norm in machine learning


