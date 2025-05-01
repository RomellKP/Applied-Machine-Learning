**Projects for Applied Machine Learning**:

**Project 1:**

  **Description:**  
  

  **Features:**  
    
  
  **Run and Compile:**  

  
  **My Contributions:**  


**Project 2:**  

  **Description:**  
 

  **Features**  
  
  
  **Run and Compile:**  
  
  
  **My Contributions:**  
  

**Project 3:**

  **Description:**  
  

 **Features**  
 
  
  **Run and Compile:**  
  
  
  **My Contributions:**  

  # White Wine Quality Prediction with PyTorch

This project uses machine learning models built from scratch in PyTorch to predict the quality of white wine based on its physicochemical attributes. It includes detailed data visualization, model training via gradient descent, and evaluation using custom accuracy metrics and cross-validation.

## 📊 Dataset

The dataset (`WhiteWine.txt`) contains 4898 white wine samples with the following features:

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (target)

## 🔧 Features

### 📈 Data Visualization

Visual tools help understand relationships and distributions:
- `countplot` of wine quality
- `histplot` with KDE of alcohol content
- `jointplot` between alcohol and density
- Correlation heatmap
- `violinplot` of predicted vs actual quality

### 🤖 Custom ML Models

Three models are implemented with manual gradient descent:

1. **Linear Regression** – using only alcohol as input  
2. **Multi-linear Regression** – using multiple normalized features  
3. **Non-linear Regression** – includes feature interactions

All models are trained using PyTorch tensors with custom backpropagation and optimization logic.

### 📏 Evaluation

Accuracy is calculated based on a *thresholded difference* between predicted and actual wine quality scores.

- Accuracy is reported at thresholds: **0.25**, **0.5**, **1.0**
- Models are evaluated using **5-fold cross-validation**

### 🧪 Sample Results

**Linear Model**  
- T=0.25 → 99.5%  
- T=0.5 → 100%  
- T=1.0 → 100%

**Multi-linear Model**  
- T=0.25 → 91.8%  
- T=0.5 → 99.7%  
- T=1.0 → 100%

**Non-linear Model**  
- T=0.25 → 92.3%  
- T=0.5 → 99.8%  
- T=1.0 → 100%

## 🧰 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- PyTorch (manual autograd and optimization)
- scikit-learn (for K-Fold splitting)

## 📂 Project Structure

  
