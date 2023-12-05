---

# Machine Learning and Statistics Repository

This repository contains separate tasks labeled from 1 to 5, addressing distinct analyses related to the Square root, chi-squared testing, t-testing, the Iris data set, Principal Component Analysis,  and an independent Iris dataset project.

## Requirements:

- Python 3.11.4 or later
- Jupyter Notebooks (detailed below)
- Libraries: pandas, matplotlib, scikit-learn (imports detailed in notebook)


## How to Use

1. **Clone the Repository:**
   ```bash
    git clone https://github.com/nexlanglxm/machine-learning-and-statistics.git
    ```
2. **Open the folder with:**
   - Jupyter Notebook,
   - JupyterLab or
   - Visual Studio Code (with Jupyter support installed)
3. **Navigate to the Specific Task:**
   - For Tasks:
   Access the `tasks.ipynb` file.
   - For Iris Dataset Project: Open and explore the `project.ipynb` file.

## Task 1: Square root using Newton's Method

Square roots are difficult to calculate. In Python, you typically use the power operator (a double asterisk) or a package such as `math.` In this task, you should write a function `sqrt(x)` to approximate the square root of a floating point number x without using the power operator or a package.

Rather, you should use the Newton’s method. Start with an initial guess for the square root called $z_0$. You then repeatedly improve it using the following formula, until the difference between some previous guess $z_i$ and the next $z_{i+1}$ is less than some threshold, say 0.01.

## Task 2: scipy

Consider the below contingency table (see task) based on a survey asking respondents whether they prefer coffee or tea and whether they prefer plain or chocolate biscuits. Use scipy.stats to perform a chi-squared test to see whether there is any evidence of an association between drink preference and biscuit preference in this instance.

## Task 3: t-testing

Perform a t-test on the famous penguins data set to investigate whether there is evidence of a significant difference in body mass of male and female gentoo penguins.

## Task 4: Iris

Using the famous iris data set, suggest whether the setosa class is easily separable from the other two classes. Provide evidence for your answer.

## Task 5: PCA

Perform Principal Component Analysis on the iris data set, reducing the number of dimensions to two. Explain the purpose of the analysis and your results.

# Iris Dataset Project

## Overview:
This project aims to explore classification algorithms using the famous Iris flower dataset associated with Ronald A Fisher. The focus is on demonstrating an understanding of supervised learning, classification algorithms, and implementing at least one common classification algorithm using the scikit-learn Python library.

## Contents of Notebook Files:

- **Introduction to Supervised Learning**:
  - Definition and principles of supervised learning.
  - Importance of labeled data for training.

- **Understanding Classification Algorithms**:
  - Explanation of classification algorithms in supervised learning.
  - Discussion on the significance of classifying data.

- **Exploring the Iris Dataset**:
  - Data visualization, statistical analysis, and characteristics of the Iris dataset.

- **Introduction to Learning Algorithms: K-Nearest Neighbors & Support Vector Machines**:
  - Explanation of k-NN/SVM and their roles in classification tasks.
  - The principles of each explored.
  - Concepts like hyperplanes, support vectors, and kernel functions.
  - Explanation as to the applications of each.

- **Implementation of chosen algorithm using scikit-learn**:
  - Code walkthrough demonstrating the implementation of a k-NN classifier on the Iris dataset.
  - Evaluation metrics and visualizations to assess the classifier's performance.

## References:
- List of resources, articles, and documentation referred to during the project.
- 
> This repository was created for the Machine Learning and Statistics module, Higher Diploma in Science in Data Analytics at Atlantic Technological University, September to December 2023.
---
