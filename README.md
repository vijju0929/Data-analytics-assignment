# Smart Crop Recommendation System

##  Project Overview

The **Smart Crop Recommendation System** is a Machine Learning-based project that recommends the most suitable crop to grow based on soil nutrients and environmental conditions.

The system analyzes agricultural parameters such as nitrogen, phosphorus, potassium, temperature, humidity, soil pH, and rainfall to predict the appropriate crop.

This project combines **Data Analytics, Data Visualization, and Machine Learning** to demonstrate how data-driven approaches can support agricultural decision-making.

---

## Project Objective

The main objective of this project is to develop a Machine Learning model that recommends suitable crops based on soil and climatic conditions.

The project aims to:

- Analyze agricultural data.
- Understand relationships between soil and climatic parameters.
- Perform data cleaning and preprocessing.
- Create meaningful data visualizations.
- Train a Machine Learning model.
- Evaluate model performance.
- Predict suitable crops based on input parameters.

---

## Dataset

The dataset was obtained from Kaggle.

**Dataset:** Crop Recommendation Dataset

**Dataset Source:** [Kaggle – Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

### Dataset Features

| Feature | Description |
|---|---|
| N | Nitrogen content in soil |
| P | Phosphorus content in soil |
| K | Potassium content in soil |
| Temperature | Environmental temperature |
| Humidity | Relative humidity |
| pH | Soil pH value |
| Rainfall | Rainfall amount |
| Label | Recommended crop |

### Target Variable

**Label** – The crop recommended based on the given agricultural and environmental parameters.

---

## Machine Learning Algorithm

### Random Forest Classifier

Random Forest is a Machine Learning algorithm that combines multiple decision trees to make predictions.

It is used in this project to classify agricultural conditions into suitable crop categories.

### Why Random Forest?

- Handles multiple input features.
- Suitable for classification problems.
- Can capture complex relationships between variables.
- Reduces overfitting compared with a single decision tree.
- Provides feature importance values.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Project Workflow

1. Dataset collection from Kaggle
2. Data loading
3. Data exploration
4. Data cleaning
5. Handling missing values and duplicate records
6. Exploratory Data Analysis (EDA)
7. Data visualization
8. Feature selection
9. Label encoding
10. Train-test splitting
11. Random Forest model training
12. Crop prediction
13. Model evaluation
14. Feature importance analysis
15. Saving project files

---

## Data Visualizations

The project includes the following visualizations:

1. Crop Distribution
2. Agricultural Feature Distributions
3. Correlation Heatmap
4. Boxplots of Agricultural Features
5. Rainfall Distribution Across Crops
6. Temperature vs Humidity Scatter Plot
7. Confusion Matrix
8. Model Performance Metrics
9. Feature Importance

These visualizations help understand the dataset, identify patterns, analyze relationships between agricultural features, and interpret the model.

---

## 📏 Model Evaluation Metrics

The model is evaluated using:

- **Accuracy** – Overall percentage of correct predictions.
- **Precision** – Measures the correctness of positive predictions.
- **Recall** – Measures how many actual positive cases were identified.
- **F1-score** – Harmonic mean of precision and recall.
- **Confusion Matrix** – Displays correct and incorrect predictions.
- **Cross-validation** – Evaluates model performance across multiple data splits.

### Model Performance

> Update this section after running the model with your actual results.

| Metric | Score |
|---|---|
| Accuracy | Add your result |
| Precision | Add your result |
| Recall | Add your result |
| F1-score | Add your result |
| Cross-validation Accuracy | Add your result |

---

## 🌾 Crop Prediction

The model accepts the following input parameters:

- Nitrogen
- Phosphorus
- Potassium
- Temperature
- Humidity
- Soil pH
- Rainfall

Based on these values, the trained Random Forest model predicts a suitable crop.

---

## Project Structure

```text
Smart-Crop-Recommendation-System/
│
├── README.md
├── Crop_Recommendation_Dataset.csv
├── cleaned_crop_dataset.csv
├── random_forest_crop_model.pkl
├── crop_label_encoder.pkl
├── evaluation_results.json
├── model_evaluation_results.csv
├── classification_report.txt
├── feature_importance.csv
│
└── visualizations/
    ├── 01_crop_distribution.png
    ├── 02_feature_distributions.png
    ├── 03_correlation_heatmap.png
    ├── 04_boxplots.png
    ├── 05_rainfall_by_crop.png
    ├── 06_temperature_humidity_scatter.png
    ├── 07_confusion_matrix.png
    ├── 08_model_performance_metrics.png
    └── 09_feature_importance.png
```

---

##  Key Findings

> Update this section after analyzing your actual model outputs.

- Agricultural parameters play an important role in crop recommendation.
- Soil nutrient levels and environmental conditions can help distinguish crop requirements.
- Data visualization helps identify patterns and relationships in agricultural data.
- Machine Learning can be used to classify crops based on soil and climatic parameters.
- Random Forest provides a data-driven approach to crop recommendation.

---

##  Conclusion

The Smart Crop Recommendation System demonstrates the application of Data Analytics and Machine Learning in agriculture. By analyzing soil nutrient levels and environmental conditions, the system predicts a suitable crop using the Random Forest Classifier.

The project includes data preprocessing, exploratory data analysis, visualizations, model training, and performance evaluation. It demonstrates how Machine Learning techniques can be applied to agricultural datasets to support data-driven crop selection.

This project is developed for **educational purposes**. Real-world crop selection should also consider local agricultural conditions, soil testing, farming practices, and advice from agricultural experts.

---

##  Author

**Vijaykumar B**

---

##  References

- Kaggle Crop Recommendation Dataset
- Scikit-learn Documentation
- Pandas Documentation
- Matplotlib Documentation
- Seaborn Documentation
