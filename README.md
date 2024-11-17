# Machine Learning for Human Movement Classification Based on Kinect Skeleton Data

## Abstract
This thesis conducts a detailed comparative study of several Machine Learning models, focusing on their application to Kinect skeleton data for classifying human movements. The research evaluates models such as Support-Vector Machines, Random Forests, Linear Regression, among others, for their accuracy, efficiency, and robustness in this task. Using a dataset of movements captured through a Microsoft Kinect, the study employs pre-processing, feature extraction, and model evaluation to assess performance metrics like accuracy, precision, recall, and F1 score.

The findings highlight the strengths and limitations of each model, offering insights for researchers and professionals in the field. The results set a foundation for developing more accurate and efficient systems for human movement classification.

## Thesis Contents

### 1. Introduction
- **Problem Statement**: The potential of Kinect sensor data for cost-effective and accurate movement classification.
- **Literature Review**: Overview of existing studies using Kinect data in rehabilitation, sports, and fall risk assessment.
- **Dataset Overview**: Movements captured from 22 individuals using Kinect.
- **Objectives**: Steps to classify movements effectively using Machine Learning.

### 2. Dataset Analysis
- **Data Collection**: Methodology and setup using Microsoft Kinect and PyKinect2.
- **Data Structure**: Organization of 3D coordinates for various movements.
- **Pre-Processing**: Noise removal, normalization, and transformation for machine learning tasks.

### 3. Methodology
- **Overview of Models**: Random Forests, Gradient Boosting, Logistic Regression, Multi-layer Perceptron, etc.
- **Data Splitting Techniques**: Effective methods to avoid data leakage.
- **Feature Engineering**: Extraction of meaningful features like duration, velocity, and displacement.

### 4. Results and Discussion
- **Models Evaluation**: Performance comparison using metrics such as accuracy, F1 score, recall, precision, and MCC.
- **Exploratory vs. Effective Approaches**: Lessons learned from initial implementations.
- **Movement Similarities**: Challenges in differentiating between similar movements like "Mat Walk" and "Hoop Walk."

### 5. Conclusions
- **Key Discoveries**: Importance of data pre-processing, feature engineering, and effective splitting methods.
- **Limitations**: Small dataset size and the presence of noisy or mislabeled data.
- **Future Work**: Suggestions for using larger datasets, new features, and advanced models like CNNs and LSTMs.

## Disclaimer
The source code and dataset used in this thesis are the intellectual property of the research group associated with this work. I do not own the rights to share or disclose them publicly. Access to these resources is restricted and requires explicit permission from the research group or the rightful owners. Please refer to the thesis document for methodological details and results.

## Author
- Lucian Dorin Crainic
- Bachelor’s Degree in Computer Science
- Faculty of Information Engineering, Computer Science, and Statistics
- Email: crainic.lucian@gmail.com