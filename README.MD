# Artificial Neural Networks for Regression

## Directions and Overview

The main purpose of this assignment is to gain experience using artificial neural networks (ANNs) to solve simple regression problems. In this assignment, you will fit a neural network to a noisy 3D sinusoidal data set. Using a `Sequential` model, you will manually adjust hyperparameter values and observe their influence on the model's predictions. This process involves manually sweeping the hyperparameter space to hone in on reasonable values through a guess-and-check method: pick some values, train the model, observe the prediction curve, and repeat.

### Objectives

1. **Manual Hyperparameter Tuning**:
   - Experiment with various hyperparameters and observe their effects on the model's predictions.
   - Develop an intuitive understanding of how different hyperparameters influence the performance of the neural network.

2. **Model Training and Evaluation**:
   - Build and train an ANN that models the data reasonably well.
   - Aim to achieve a smoother and less erratic prediction curve.
   - Visualize the model's prediction curve alongside the training data.
   - Compute and analyze the generalization error on the test set.

### Key Hyperparameters to Explore

- Number of nodes per layer
- Number of layers
- Activation functions
- Normalization method (should be negligible)
- Number of epochs
- Learning rate
- Loss function

### Learning Outcomes

- **Hands-on Experience**: Gain practical experience with building and training ANNs for regression tasks.
- **Hyperparameter Tuning**: Understand the impact of different hyperparameters on the performance and predictions of neural networks.
- **Model Evaluation**: Learn to evaluate and visualize the performance of ANNs.
- **Critical Analysis**: Develop the ability to critically analyze and interpret model results.

## Steps to Complete the Assignment

### Data Preparation

1. **Load the Data**:
   - Load the noisy 3D sinusoidal data set.
   - Split the data into training and testing sets.

### Model Building and Training

2. **Build the Neural Network**:
   - Use the `Sequential` model from a neural network library (e.g., Keras).
   - Experiment with different numbers of layers and nodes per layer.
   - Try various activation functions (e.g., ReLU, sigmoid, tanh).

3. **Hyperparameter Tuning**:
   - Manually adjust hyperparameters such as the learning rate, number of epochs, and loss function.
   - Train the model and observe the prediction curve.
   - Repeat the process to refine the hyperparameters and improve the model's predictions.

### Model Evaluation and Visualization

4. **Evaluate the Model**:
   - Compute the model's predictions on the test set.
   - Calculate the generalization error.

5. **Visualize Predictions**:
   - Plot the model's prediction curve alongside the training data.
   - If the trendline looks erratic, plot the model's predictions using a scatter plot.
   - Ensure the final submission includes a connected line plot of the prediction curve.

### Finalizing the Model

6. **Achieve a Reasonable Model**:
   - Ensure the model's prediction curve looks reasonable and smooth.
   - Fine-tune the model by further adjusting hyperparameters if necessary.

### Critical Analysis and Reporting

7. **Critical Analysis**:
   - Discuss the influence of different hyperparameters on the model's performance.
   - Explain the process of achieving a smooth and less erratic prediction curve.
   - Analyze the generalization error and overall performance of the model.

8. **Report Findings**:
   - Summarize the results of the manual hyperparameter tuning process.
   - Highlight key insights and learning outcomes from the assignment.

By completing this assignment, you will build a strong foundation in using ANNs for regression tasks, understand the importance of hyperparameter tuning, and develop skills in evaluating and visualizing model performance.
