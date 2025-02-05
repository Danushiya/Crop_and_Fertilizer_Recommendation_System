# Crop and Fertilizer Recommendation System

This repository contains the **Crop and Fertilizer Recommendation System** project, which involves data analysis, visualization, feature engineering, and machine learning techniques to provide insights into agricultural data. The project is divided into **Week 1, Week 2, and Week 3** tasks, focusing on **Exploratory Data Analysis (EDA), Feature Engineering, and Model Preparation** for better predictions.

---

## Key Features

- **Week 1: Basic Data Exploration**
  - Understanding dataset structure, missing values, and data types.
  - Generating summary statistics and visualizations.
  - Initial insights into crop and fertilizer data.

- **Week 2: Advanced Data Analysis & Feature Engineering**
  - Visualizing feature distributions and relationships.
  - Identifying outliers using boxplots.
  - Performing correlation analysis and encoding categorical features.

- **Week 3: Train-Test Split, Feature Scaling & Encoding**
  - Splitting data into training and testing sets.
  - Applying StandardScaler for feature scaling.
  - Encoding categorical target variables.
  - Preparing the dataset for machine learning models.

---

## Table of Contents

1. [Installation](#installation)
2. [Technologies Used](#technologies-used)
3. [Datasets](#datasets)
4. [Week 1: Exploratory Data Analysis (EDA)](#week-1-exploratory-data-analysis-eda)
5. [Week 2: Advanced Data Analysis & Feature Engineering](#week-2-advanced-data-analysis--feature-engineering)
6. [Week 3: Train-Test Split, Feature Scaling & Encoding](#week-3-train-test-split-feature-scaling--encoding)
7. [Project Workflow](#project-workflow)

---

## Installation

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Libraries:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Danushiya/Crop_and_Fertilizer_Recommendation_System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Crop_and_Fertilizer_Recommendation_System
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Technologies Used

- **Programming Language**: Python
- **Visualization Tools**: Matplotlib, Seaborn
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-learn

---

## Datasets

1. **Crop Recommendation Dataset**:
   - Provides information about various soil and environmental parameters (e.g., nitrogen, phosphorus, potassium, temperature, humidity, etc.) and their corresponding crops.

2. **Fertilizer Prediction Dataset**:
   - Contains details about soil types, crop types, and suitable fertilizers for better yield.

---

## Week 1: Exploratory Data Analysis (EDA)

The Week 1 task focuses on:
- **Basic Exploration**:
  - Viewing the first and last few rows of the dataset.
  - Checking dataset shape, column details, and data types.
  - Identifying missing and duplicate values.
- **Statistical Analysis**:
  - Summary statistics of numerical features.
  - Distribution of target features.
- **Visualizations**:
  - Pair plots for relationships between features.
  - Heatmaps for correlations.
  - Distribution plots and count plots for categorical variables.

---

## Week 2: Advanced Data Analysis & Feature Engineering

The Week 2 task includes:
- **Feature Distributions**:
  - Histograms for each numerical feature.
- **Feature vs Target Relationships**:
  - Scatter plots between features and crop labels.
- **Outlier Detection**:
  - Boxplots to identify extreme values.
- **Correlation Analysis**:
  - Heatmaps to analyze feature relationships.
- **Encoding Categorical Features**:
  - Mapping crop labels to numerical values for machine learning.

---

## Week 3: Train-Test Split, Feature Scaling & Encoding

The Week 3 task includes:
- **Train-Test Split**:
  - Splitting dataset into 80% training and 20% testing sets.
- **Feature Scaling**:
  - Applying StandardScaler to normalize feature values.
- **Encoding Categorical Variables**:
  - Using Label Encoding or custom mapping for categorical features.
- **Dataset Preparation**:
  - Ensuring data is preprocessed and ready for model training.

---

## Project Workflow

1. **Dataset Loading**:
   - Load the `Crop_Recommendation.csv` and `Fertilizer_Prediction.csv` datasets.

2. **Week 1 - EDA**:
   - Perform data cleaning, missing value handling, and visualization.

3. **Week 2 - Feature Engineering**:
   - Analyze trends, detect outliers, and apply feature transformations.

4. **Week 3 - Train-Test Split, Scaling & Encoding**:
   - Split the dataset into training and testing sets.
   - Normalize numerical features to improve model performance.
   - Encode categorical variables for machine learning.

5. **Visualization**:
   - Generate visually appealing plots to communicate findings effectively.

---

