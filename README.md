# Neural-Ordinary-Differential-Equations
Neural Ordinary Differential Equations for Time Series Analysis

At this repository you can find the code that implements the Neural Differential Equation algorithm. The code is commented in detail. Also you can check my report on Neural ODEs: "Understanding the Neural ODEs.pdf", where I describe the idea, intuition and math behind the algorithm, followed by a thorough
breakdown of its implementation.

## From ResNet to Neural ODE
<img src="https://github.com/davudtopalovic/Neural-Differential-Equations/assets/117101265/b069cba1-9b9c-4252-bbbb-c7b2307744bd" alt="Image description" width="400">

## Representing an ODE in form of Neural Network Layer
<img src="https://github.com/davudtopalovic/Neural-Differential-Equations/assets/117101265/ee8d19aa-28e1-4067-b7c7-ae65c5f7fa99" alt="Image description" width="400">

## Learning the dynamics of Time Series Data
<img src="https://github.com/davudtopalovic/Neural-Differential-Equations/assets/117101265/6dd62447-30cd-4251-9fac-98262db6e425" alt="Image description" width="600">

##  Forward pass and Backward pass(with Adjoint Sensitivity method)
<img src="https://github.com/davudtopalovic/Neural-Differential-Equations/assets/117101265/6955da18-f323-4274-9fb5-ee4968a72827" alt="Image description" width="600">
<img src="https://github.com/davudtopalovic/Neural-Differential-Equations/assets/117101265/12b33438-fca0-49d9-95f6-d36ba8ad4127" alt="Image description" width="600">

## Visualizing the training and results
$`
\frac{dz}{dt} = 
\begin{bmatrix}
-0.1 & 2.0 \\
-2.0 & -0.1 \\
\end{bmatrix} z^3 
\quad \text{with} \quad  \begin{bmatrix}z_1\\z_2\end{bmatrix}(0) \begin{bmatrix}0.0\\2.0\end{bmatrix}
`$

<img src="https://github.com/davudtopalovic/Neural-Differential-Equations/assets/117101265/9deb3ee3-b511-4c5b-94bb-72337db45d00" alt="Image description" width="500" height="500">

## GIF
$`\frac{dz}{dt} = \begin{bmatrix}-0.1 & -1.0\\1.0 & -0.1\end{bmatrix} z \quad \text{with} \quad  \begin{bmatrix}z_1\\z_2\end{bmatrix}(0) \begin{bmatrix}0.6\\0.3\end{bmatrix}`$

<img src="https://github.com/davudtopalovic/Neural-Differential-Equations/assets/117101265/4ebfc460-6c0d-44aa-b518-1a3531ca7c0f" alt="Image description" width="500">
