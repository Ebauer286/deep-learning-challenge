Deep Learning Challenge - Alphabet Soup Funding Predictor

Project Overview

This repository contains a machine learning solution for Alphabet Soup, a nonprofit foundation that wants to better predict which funding applicants have the highest probability of success. The project uses deep learning techniques to create a binary classifier model that predicts whether applicants will be successful if funded based on various organizational features.

---

Dataset

The analysis uses a dataset of over 34,000 organizations that have received funding from Alphabet Soup. The dataset includes metadata columns such as:
    -Application type
    -Affiliated industry sector
    -Government organization classification
    -Funding use case
    -Organization type
    -Status
    -Income classification
    -Special considerations
    -Funding amount requested
    -Whether the money was used effectively (target variable)

---
    
Repository Structure
    -AlphabetSoupCharity.ipynb: Jupyter notebook containing the initial model development, including data preprocessing, model creation, training, and evaluation
    -AlphabetSoupCharity_Optimization.ipynb: Jupyter notebook containing the optimized model development with various techniques to improve performance
    -AlphabetSoupCharity.h5: HDF5 file containing the saved initial neural network model
    -Neural_Network_Model_Report.md: Detailed report on the analysis, results, and recommendations

---

Methodology

The project follows these key steps:

1. Data Preprocessing
    -Removal of non-beneficial ID columns
    -Binning of rare categorical values
    -Encoding of categorical variables
    -Splitting data into training and testing sets
    -Feature scaling
    
2. Model Development
    -Creation of a multi-layer neural network using TensorFlow/Keras
    -Compilation with binary cross-entropy loss and adam optimizer
    -Model training and evaluation

3. Model Optimization
    -Adjustment of preprocessing techniques
    -Modification of neural network architecture
    -Fine-tuning of training parameters

---

Results

The initial model achieved approximately 73% prediction accuracy. After optimization efforts, the improved model exceeded the target performance threshold of 75%, reaching approximately 76% accuracy.

---

Technologies Used
    -Python
    -Pandas
    -Scikit-learn
    -TensorFlow
    -Keras
    -Jupyter Notebook

---
    
Conclusions

The neural network model successfully predicts funding effectiveness based on organizational characteristics. However, a more interpretable model like Random Forest is recommended for additional insights into feature importance.

---

Code Attribution

---

All code in this repository was developed by Elizabeth for the Module 21 Challenge of the Data Analytics Bootcamp. Any code snippets or techniques borrowed from external sources are properly cited in the respective notebooks. Additionally, this assignment was completed with the assistance of Xpert Bot and tutoring sessions.

License
This project is licensed under the MIT License - see the LICENSE file for details.