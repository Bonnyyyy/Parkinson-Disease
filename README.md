# Parkinson's Disease Prediction

This project aims to develop a machine learning model to predict Parkinson's disease based on various voice-related features. The model leverages data from the UCI Machine Learning Repository to provide insights into the early detection of Parkinson's disease, which is crucial for effective management and treatment.

## Project Overview

Parkinson's disease is a progressive neurological disorder that affects movement. Early diagnosis can significantly improve the quality of life for patients. This project focuses on creating a predictive model that utilizes voice features, which have been shown to correlate with Parkinson's symptoms. By analyzing these features, we aim to provide a tool for healthcare professionals to assist in early diagnosis.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains various features extracted from voice recordings of individuals, with a binary classification target indicating the presence of Parkinson's disease.

- **Source**: [Parkinson's Disease Data Set](https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/parkinsons.data)

### Features Included:
- MDVP: Jitter (%)
- MDVP: Jitter (Abs)
- MDVP: RAP
- MDVP: PPQ
- MDVP: Shimmer
- MDVP: Shimmer (dB)
- Additional voice-related metrics...

## Methodology

1. **Data Preprocessing**: 
   - Loaded the dataset and performed initial exploration to understand its structure and contents.
   - Handled missing values and duplicates, ensuring a clean dataset for analysis.

2. **Data Visualization**: 
   - Visualized the distribution of the target variable and the relationship between features using Seaborn and Matplotlib to gain insights into the data.

3. **Handling Class Imbalance**: 
   - Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset, ensuring robust model training.

4. **Model Development**: 
   - Implemented a Decision Tree Classifier, leveraging GridSearchCV for hyperparameter tuning to enhance model performance.

5. **Model Evaluation**: 
   - Assessed the model using confusion matrix, classification report, and ROC curve to understand its accuracy and effectiveness.

## Results

The model demonstrated promising results in predicting Parkinson's disease, with metrics indicating strong classification performance. The visualizations of the confusion matrix and ROC curve further illustrated the model's capabilities.

## Acknowledgments

This project was developed collaboratively with Souvik Mukherjee. Special thanks to him for his contributions and support throughout the development process.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please create an issue or submit a pull request. Your feedback and collaboration can help enhance the project's impact and functionality.
