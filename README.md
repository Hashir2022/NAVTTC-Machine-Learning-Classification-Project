# NAVTTC | Machine Learning & Deep Learning Classification Project

<p align="center">
  <img src="assets/navttc-banner.png" alt="NAVTTC Machine Learning Project Banner" width="100%">
</p>

<h3 align="center">Turning Data into Insights Through Machine Learning</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Machine%20Learning-Classification-orange">
  <img src="https://img.shields.io/badge/Deep%20Learning-MLP-purple">
  <img src="https://img.shields.io/badge/Scikit--learn-Modeling-orange?logo=scikitlearn">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter">
  <img src="https://img.shields.io/badge/Training-NAVTTC-success">
</p>

---

## 1. Project Overview

This project, **Classification Using Machine Learning and Deep Learning Models**, was developed as a practical final project during the NAVTTC Machine Learning Training Program.

The main objective is to analyze demographic and employment-related data and predict whether an individual's annual income exceeds **$50,000** using different classification algorithms.

The project follows an end-to-end machine learning workflow, starting from data exploration and preprocessing to model development, evaluation, visualization, and interactive model comparison.

It demonstrates practical implementation of Python, data analysis, machine learning, deep learning concepts, and model evaluation techniques.

## 2. Project Objectives

- Understand and explore a real-world dataset.
- Perform data cleaning and preprocessing.
- Identify important patterns and relationships in the data.
- Implement multiple machine learning classification algorithms.
- Explore a neural network-based classification approach.
- Evaluate and compare model performance.
- Identify the best-performing model.
- Develop an interactive interface to explore model evaluation results.

## 3. Dataset Information

**Dataset:** Adult Income Dataset  
**Source:** Kaggle  
**Problem Type:** Binary Classification

| Dataset Attribute | Details |
|---|---|
| Total Records | 48,842 |
| Total Features | 15 |
| Target Variable | Income |
| Dataset Type | Structured Tabular Data |
| Prediction Classes | <=50K and >50K |

**Prediction Goal:** Determine whether an individual's annual income is greater than $50,000 based on available dataset attributes.

## 4. Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Jupyter Notebook | Development environment |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Plotly | Interactive visualizations |
| Scikit-learn | Machine learning algorithms and evaluation |
| ipywidgets | Interactive notebook interface |

## 5. Project Workflow

The project follows these major stages:

**Stage 1 – Data Collection**
- Load the Adult Income Dataset.
- Inspect dataset structure, dimensions, and data types.

**Stage 2 – Exploratory Data Analysis (EDA)**
- Analyze numerical and categorical features.
- Explore distributions and relationships.
- Identify patterns and potential data quality issues.

**Stage 3 – Data Cleaning**
- Handle missing and inconsistent values.
- Identify and analyze duplicate records.
- Prepare the dataset for machine learning.

**Stage 4 – Data Preprocessing**
- Handle missing values represented by `?`.
- Apply label encoding to categorical features.
- Perform feature scaling where required.
- Split the dataset into training and testing sets.

**Stage 5 – Model Development**
- Implement five classification algorithms.
- Train models using prepared training data.
- Generate predictions on test data.

**Stage 6 – Model Evaluation**
- Calculate accuracy.
- Generate classification reports.
- Analyze confusion matrices.
- Visualize ROC curves.
- Examine feature importance where supported.
- Apply cross-validation and compare training performance.

**Stage 7 – Interactive Model Comparison**
- Build an interactive interface using ipywidgets.
- Select and inspect classification models.
- Display evaluation reports and confusion matrices.
- Compare model performance.

## 6. Machine Learning Models

Five classification approaches were implemented:

| No. | Algorithm | Category |
|---|---|---|
| 01 | Logistic Regression | Machine Learning |
| 02 | Decision Tree Classifier | Machine Learning |
| 03 | Random Forest Classifier | Ensemble Learning |
| 04 | Support Vector Machine (SVM) | Machine Learning |
| 05 | Neural Network (MLP Classifier) | Deep Learning |

### Model Descriptions

**1. Logistic Regression**

A supervised classification algorithm used as a baseline approach for predicting income categories.

**2. Decision Tree Classifier**

A tree-based algorithm that makes predictions through a sequence of feature-based decisions.

**3. Random Forest Classifier**

An ensemble learning technique that combines multiple decision trees to improve predictive performance and robustness.

**4. Support Vector Machine (SVM)**

A supervised learning algorithm that identifies an optimal decision boundary between classification categories.

**5. Neural Network (MLP Classifier)**

A multi-layer perceptron model used to explore neural network-based classification and learn complex patterns in the dataset.

## 7. Model Performance & Results

The following test accuracy results were recorded during the project:

| Model | Test Accuracy |
|---|---:|
| Random Forest | **83.90%** |
| Decision Tree | 83.43% |
| Neural Network (MLP) | 81.93% |
| Support Vector Machine | 79.97% |

### Performance Visualization

<p align="center">
  <img src="https://quickchart.io/chart?width=700&height=350&c=%7Btype%3A%27bar%27%2Cdata%3A%7Blabels%3A%5B%27Random%20Forest%27%2C%27Decision%20Tree%27%2C%27Neural%20Network%27%2C%27SVM%27%5D%2Cdatasets%3A%5B%7Blabel%3A%27Test%20Accuracy%20%25%27%2Cdata%3A%5B83.90%2C83.43%2C81.93%2C79.97%5D%2CbackgroundColor%3A%5B%27%233b82f6%27%2C%27%2322c55e%27%2C%27%23f59e0b%27%2C%27%23a855f7%27%5D%7D%5D%7D%2Coptions%3A%7Bscales%3A%7By%3A%7Bticks%3A%7Bmin%3A0%2Cmax%3A100%7D%7D%7D%7D%7D" alt="Model accuracy comparison chart" width="90%">
</p>

### Best Performing Model

**Random Forest Classifier – 83.90%**

Random Forest achieved the highest recorded test accuracy among the reported models in this project.

*Note: Accuracy values are based on the recorded project results. Logistic Regression is not included in this comparison because its final comparison output was inconsistent. Results can vary with preprocessing, data splitting, and model configuration.*

## 8. Model Evaluation Techniques

The following evaluation methods were used to assess model performance:

- Accuracy Score
- Classification Report
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Cross-Validation
- Feature Importance
- Training Time Comparison

These techniques provide a broader understanding of model performance beyond accuracy alone.

## 9. Interactive Model Comparison

An interactive interface was developed using **ipywidgets** inside Jupyter Notebook.

The interface allows users to:

- Select different trained classification models.
- View model classification reports.
- Explore confusion matrices.
- Compare model evaluation results.
- Understand differences between model predictions.

This feature makes the project more interactive and improves the interpretation of machine learning results.

## 10. Project Structure

Suggested repository structure:

```text
NAVTTC-Machine-Learning-Classification/
│
├── assets/
│   ├── navttc-banner.png
│   ├── model-comparison.png
│   ├── confusion-matrix.png
│   └── roc-curve.png
│
├── notebooks/
│   └── machine-learning-classification.ipynb
│
├── README.md
├── requirements.txt
└── LICENSE
```

*Update the notebook filename and folders according to the actual files in your repository.*

## 11. Installation & Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### Step 2: Navigate to the Project

```bash
cd YOUR-REPOSITORY
```

### Step 3: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly ipywidgets jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Project

Open the classification notebook and execute the cells sequentially.

**Requirement:** Make sure the Adult Income Dataset is downloaded and placed at the file path expected by the notebook.

## 12. Key Learning Outcomes

Through this project, I gained hands-on experience in:

- Python programming for data science.
- Exploratory Data Analysis and data visualization.
- Data cleaning and preprocessing.
- Feature encoding and scaling.
- Supervised machine learning algorithms.
- Neural network-based classification.
- Model evaluation and performance comparison.
- Interactive analytical interfaces.
- Working with real-world structured datasets.

## 13. Future Improvements

Potential improvements for future development include:

- Hyperparameter optimization.
- Advanced feature engineering.
- Addressing class imbalance.
- Improved model interpretability using SHAP.
- Deployment through a Streamlit web application.
- A user-friendly income prediction interface.
- Additional model comparison and optimization.

## 14. Training & Project Information

| Detail | Information |
|---|---|
| Training Program | NAVTTC Machine Learning Training |
| Training Duration | February – May |
| Project Type | Final Project |
| Domain | Data Science & Machine Learning |
| Programming Language | Python |
| Development Environment | Jupyter Notebook |

## 15. About the Author

**Engr. Hashir Ahmed Buriro**  
Software Engineer | Python Developer | Data Science & Machine Learning Enthusiast

I am a Software Engineering graduate interested in Python development, data analytics, machine learning, and building practical technology solutions.

This project represents my practical learning and implementation experience during the NAVTTC Machine Learning Training Program.

<p align="center">
  <a href="https://github.com/Hashir2022">
    <img src="https://img.shields.io/badge/GitHub-Hashir2022-181717?style=for-the-badge&logo=github">
  </a>
  <a href="https://www.linkedin.com/in/engr-hashir-ahmed-buriro/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin">
  </a>
</p>

---

<p align="center">
  <b>Thank you for visiting this project!</b><br>
  If you find this project useful, consider giving it a ⭐ on GitHub.
</p>

<p align="center">
  <i>Learning • Building • Innovating with Data</i>
</p>
