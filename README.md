# Quark-Gluon-Discriminator


## Introduction
In this lecture, we will cover the basics of Multivariate Analysis (MVA) classifiers, which are widely used in machine learning applications for classification tasks. MVA classifiers are designed to separate data points into distinct categories based on multiple input features.

### What is Classification?
Classification is a type of supervised learning where the goal is to assign a label to an input feature vector. In particle physics, for example, a common classification task is to distinguish signal events (like b-jets) from background events (like light jets).

## Types of MVA Classifiers

There are various classifiers used for MVA, including:

1. **Linear Discriminant Analysis (LDA)**
   - Based on finding a linear combination of features that separates different classes.
   - Suitable for linearly separable data.

2. **Decision Trees**
   - Classify data by recursively splitting the dataset based on feature values.
   - Can easily handle both categorical and continuous data.
   - Tend to overfit, but this can be mitigated by methods like pruning.

3. **Random Forest**
   - An ensemble learning method that creates multiple decision trees.
   - The output class is the mode of the classes predicted by individual trees.
   - Helps reduce overfitting compared to a single decision tree.

4. **Boosted Decision Trees (BDT)**
   - Combines several weak classifiers (often decision trees) to create a stronger classifier.
   - Commonly used in particle physics experiments.

5. **Support Vector Machine (SVM)**
   - Finds the hyperplane that maximizes the margin between different classes.
   - Effective in high-dimensional spaces.

6. **Neural Networks**
   - Mimic the workings of the human brain using multiple layers of neurons.
   - Capable of learning highly non-linear decision boundaries.

## Evaluation of Classifiers

To evaluate the performance of a classifier, several metrics are commonly used:

- **Accuracy**: The percentage of correctly classified instances.
- **Precision**: The number of true positives divided by the sum of true positives and false positives.
- **Recall**: The number of true positives divided by the sum of true positives and false negatives.
- **F1 Score**: The harmonic mean of precision and recall, which balances both metrics.
- **Receiver Operating Characteristic (ROC) Curve**: A plot that shows the trade-off between true positive and false positive rates for different threshold settings.
- **Area Under the ROC Curve (AUC)**: A single scalar value to measure the classifier’s overall performance.

## Applications in Particle Physics

MVA classifiers play an important role in high-energy physics experiments, such as those conducted at CERN. They are used for tasks like:

- **Jet Identification**: Classifying jets as b-jets, c-jets, or light jets.
- **Event Reconstruction**: Distinguishing between signal and background events in particle collision data.
- **Tracking**: Identifying particle trajectories in complex detector environments.

### Example: quark-jets vs gluon Jet Classification
In tasks such as distinguishing light-quark-jets from gluon jets, features such as **track transverse momentum (track_pt)**, **impact parameter**, and **vertex reconstruction** are used as inputs to the MVA classifier.


---



