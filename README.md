# ML Explained

This repository explains the mathematics, intuition, implementation, and practical use of machine learning algorithms. Each topic is intended to include:

- Mathematical theory and assumptions
- Visual intuition and small worked examples
- Python implementations and scikit-learn examples
- Model evaluation, limitations, and practical use cases

The material is written from both a research perspective and an application/interview perspective.

## Roadmap

### 1. Regression

1. [Linear Regression](classical_ml/linear_regression/)
   - Simple and multiple linear regression
   - Matrix form: $Y = XW + b$
   - Ordinary least squares and the normal equation
   - Gradient descent
   - Train/test splitting and regression metrics
   - Saving and loading trained models
2. [Polynomial Regression](classical_ml/polynomial_regression.ipynb/plrg.ipynb)
   - Polynomial feature expansion
   - Interaction terms
   - Bias-variance trade-off
   - Underfitting and overfitting

### 2. Classification

3. Logistic Regression and Binary Logistic Regression
   - Sigmoid function and log-odds
   - Maximum likelihood and log loss
   - Decision boundaries
   - Binary and multiclass classification
4. Decision Trees
   - Entropy, information gain, and Gini impurity
   - Splitting criteria and tree depth
   - Overfitting and pruning
5. Random Forests
   - Bagging and bootstrap samples
   - Random feature selection
   - Feature importance and out-of-bag evaluation
6. Support Vector Machines (SVM)
   - Maximum-margin classification
   - Support vectors
   - Soft margins and the C parameter
   - Kernel trick
7. K-Nearest Neighbors (KNN)
   - Distance measures
   - Choosing $k$
   - Feature scaling and the curse of dimensionality
8. Naive Bayes
   - Bayes theorem
   - Conditional independence assumption
   - Gaussian, Multinomial, and Bernoulli Naive Bayes

### 3. Ensemble Methods

9. Gradient Boosting and XGBoost
	- Weak learners and additive models
	- Residual fitting
	- Regularization and practical tuning
10. CatBoost
	- Ordered boosting
	- Handling categorical features
11. LightGBM
	- Histogram-based learning
	- Leaf-wise tree growth
	- Efficiency on large datasets

### 4. Clustering and Unsupervised Learning

12. K-Means Clustering
	- Centroids and the assignment-update loop
	- Choosing the number of clusters
	- Inertia and silhouette score
13. Principal Component Analysis (PCA)
	- Covariance and variance
	- Eigenvectors and eigenvalues
	- Dimensionality reduction and visualization
14. DBSCAN
	- Density-connected points
	- Core, border, and noise points
	- Choosing `eps` and `min_samples`
15. Hierarchical Clustering
	- Agglomerative clustering
	- Linkage criteria
	- Dendrograms
16. Gaussian Mixture Models (GMM)
	- Mixture distributions
	- Soft cluster assignments
	- Expectation-Maximization

### 5. Time Series, State Estimation, and Filtering

17. Hidden Markov Models (HMM)
	- Hidden states and observations
	- Transition and emission probabilities
	- Forward, backward, and Viterbi algorithms
18. Kalman Filter
	- State-space models
	- Prediction and measurement updates
	- Gaussian noise and uncertainty estimation
19. Particle Filter
	- Sequential Monte Carlo
	- Sampling, weighting, and resampling
	- Nonlinear and non-Gaussian state estimation

### 6. Neural Networks and Deep Learning

20. Recurrent Neural Networks (RNN)
	- Sequential data and hidden states
	- Backpropagation through time
	- Vanishing and exploding gradients
21. Long Short-Term Memory (LSTM)
	- Cell state and gated memory
	- Forget, input, and output gates
22. Gated Recurrent Unit (GRU)
	- Update and reset gates
	- Comparison with LSTM
23. Transformers and Attention
	- Query, key, and value representations
	- Self-attention
	- Multi-head attention
	- Positional encoding
	- Encoder and decoder architectures

## Suggested Topic Structure

Each topic will generally follow this sequence:

1. Problem definition and intuition
2. Mathematical formulation
3. A small example built from first principles
4. A library implementation
5. Evaluation and visualization
6. Limitations and practical considerations

## Tools

The examples use Python and may use:

- NumPy
- Pandas
- Matplotlib
- scikit-learn
- SciPy
- PyTorch
- XGBoost, CatBoost, and LightGBM where appropriate

## Status

This is a growing set of notes and notebooks. New topics will be added with both theory and code as the roadmap progresses.

