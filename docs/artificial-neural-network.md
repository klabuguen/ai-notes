# What is an Artificial Neural Network?
- Computational model designed to mimic how the human brain processes information.
- Fundamental building block of modern artificial intelligence and machine learning
- The **input layer** takes in raw data and the **hidden layers** perform transformations by combining inputs with weights, biases, and activation functions
- This produces the **output layer**, or *classification*, *prediction*, or *action*

```
		_ _ _ _ 
in -> | Mystery | -> out
		- - - -
```

## Theory:
Start with a linear function:

$$
\hat{y}=x_1w_1+x_2w_2
$$
Pass through nonlinear function, $\sigma$:

$$
\hat{y}=\sigma(x_1w_1+x_2w_2)
$$
## Example:
- **Goal**: Predict whether a student passes an exam.
- In statistics, you can use a logistic regression or support vector machine. However, this problem can also be solved using ANNs.
- The ANN would have two inputs (hours slept and hours studied) into the network and a bias.
- Next, a linear weighted sum is computed and a nonlinear activation function is applied.

| ID# | x1 Studied | x2 Slept | y Result |
| --- | ---------- | -------- | -------- |
| 1   | 5          | 6        | Pass     |
| 2   | 10         | 7        | Pass     |
| ..  |            |          |          |
| N   | 7          | 5        | Fail     |

## Why are ANNs so powerful?
- ANNs are excellent at handling complex, nonlinear, and high-dimensional problems where explicit programming may be infeasible.
- 