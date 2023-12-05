# Transforming-Taxi-Transit-with-Data-Driven-Solutions

### Overview

This project focuses on predicting taxi fare prices in New York City using regression modeling techniques. The goal is to develop accurate predictive models that estimate fare prices based on various factors like pickup and dropoff locations, timestamps, distances, and other relevant features.

### Dataset

The dataset used for this project contains detailed information about NYC taxi rides, including:

* Pickup and dropoff locations
* Timestamps
* Distance traveled
* Additional features

### Approach

#### Data Preparation and Preprocessing
 - Cleaned and preprocessed the dataset, selecting relevant features for modeling.
 - Scaled numeric features using techniques like normalization or standardization.

### Regression Modeling
- Utilized different regression algorithms:
   - Multilayer Perceptron (MLP)
   - Linear Regression
   - Deep Neural Network (DNN)

- Implemented regression models using TensorFlow, leveraging GPU support for faster computations.

### Optimization Techniques
- Experimented with various optimizers:
  - Stochastic Gradient Descent (SGD)
  - Adam
  - RMSProp
- Tuned learning rates associated with each optimizer to observe their impact on model performance.

### Model Evaluation
- Evaluated model performance using metrics:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
- Identified the DNN model as superior based on lower MSE and MAE values.

### Mitigating Overfitting
- Implemented dropout layers within the DNN architecture to mitigate overfitting.
- Dropout layers enhance model generalization by randomly deactivating neurons during training.

### Results

- The DNN model exhibited superior performance, providing more accurate predictions of NYC taxi fare prices.
- Demonstrated enhanced generalization and reduced overfitting with the optimized DNN architecture.

### Conclusion

This project concludes that the Deep Neural Network model, with appropriate dropout layers and optimization techniques, delivers accurate predictions for NYC taxi fare prices. The findings showcase its superiority in accuracy and generalization on both training and unseen data.
