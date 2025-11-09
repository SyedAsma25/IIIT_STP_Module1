<h1 align="center">🧩 IIIT STP – Machine Learning Module 1 Labs</h1>

<p align="center">
  <b>By <a href="https://github.com/SyedAsma25">Syed Asma</a></b>  
  <br>
  Created using <a href="https://colab.research.google.com/">Google Colab</a>  
  <br><br>
  <img src="https://img.shields.io/badge/Module-1-blue.svg" alt="Module Badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen.svg" alt="Status Badge">
  <img src="https://img.shields.io/badge/IIIT-STP-orange.svg" alt="IIIT Badge">
</p>

---

## 📘 Overview

This repository contains my work in **IIIT Student Training Program (STP) Module 1**, implemented and documented in **Google Colab** notebooks. Each lab explores a different concept from **feature extraction** to **linear transformations** demonstrating both **theory and practice**. 
> 💡 *Focus:* Foundational ML concepts, distance-based algorithms, feature engineering, and data transformations.
---

## 🔬 Lab Descriptions

### 🎲 **Lab – Probability Primer**
**📁 File:** `Copy_of_AIML_Course_Probability_Primer.ipynb`  
**🧠 Objective:** Build intuition for probability theory as it applies to machine learning.

**📊 Details:**
- Covered **basic probability rules**: addition, multiplication, and Bayes’ theorem  
- Explored **discrete and continuous distributions** (e.g., Bernoulli, Gaussian)  
- Introduced **random variables**, **expectation**, and **variance**  
- Demonstrated the role of **probabilistic reasoning** in classification models  

**🧠 Key Concepts:**  
Probability distributions • Conditional probability • Bayes’ theorem • Random variables  

---

### 🧮 **Lab – Linear Algebra Fundamentals**
**📁 File:** `Copy_of_STP_Linear_algebra.ipynb`  
**🧠 Objective:** Strengthen understanding of linear algebra operations used in ML.

**📊 Details:**
- Reviewed **vectors, matrices, and their operations**  
- Demonstrated **dot product**, **matrix multiplication**, and **orthogonality**  
- Explained **eigenvalues**, **eigenvectors**, and their role in dimensionality reduction  
- Visualized **geometric transformations** such as rotation, scaling, and reflection  

**🧠 Key Concepts:**  
Matrix operations • Vector spaces • Eigen decomposition • Linear transformations  

---
### 🧩 **Lab 1 – Feature Extraction and Visualization**
**📁 File:** `Copy_of_STP_Module_01_Lab_01_Features.ipynb`  
**🧠 Objective:** Understand and visualize extracted features from image data.

**📊 Details:**
- Dataset: **MNIST handwritten digits**
- Extracted features:
  - Sum of pixels  
  - Hole pixels  
  - Hull pixels  
- Visualized 2D/3D feature spaces for class separation
- Explored the influence of feature selection on model performance

**🧠 Key Concepts:**  
Feature selection • Dimensionality reduction • Visualization techniques

---

### 📈 **Lab 2 – Machine Learning Metrics**
**📁 File:** `Copy_of_STP_Module_1_Lab_2_Machine_Learning_terms_and_metrics_by_Om.ipynb`  
**🧠 Objective:** Learn to evaluate ML models using various performance metrics.

**📊 Details:**
- Dataset: **California Housing**
- Implemented:
  - 1-Nearest Neighbor (1-NN)
  - Random Classifier
- Computed metrics: **Accuracy**, **Precision**, **Recall**, **F1**, **MAE**, **MSE**, **RMSE**
- Applied **Cross-Validation** for reliable performance estimation

**📈 Results:** Validation Accuracy ~34%, Test Accuracy ~35%  
**🧠 Key Concepts:** Model evaluation • Cross-validation • Error metrics

---

### 🧠 **Lab 3 – Data Augmentation**
**📁 File:** `Copy_of_STP_Module_01_Lab_03_Data_Augmentation_by_Om.ipynb`  
**🧠 Objective:** Improve model robustness through data augmentation.

**📊 Details:**
- Dataset: **MNIST**
- Augmentation techniques:
  - Rotation
  - Shear transformations
- Applied **grid search** to find optimal transformation angles
- Accuracy improved from **64.7% → 68.5%**

**🧠 Key Concepts:** Data diversity • Augmentation strategy • Robustness improvement

---

### 🧮 **Lab 4 – Transforming Data using Linear Algebra**
**📁 File:** `Copy_of_STP_Module_01_Lab_04_Transforming_data_using_linear_algebra_by_Om.ipynb`  
**🧠 Objective:** Understand how linear algebra transformations impact ML data.

**📊 Details:**
- Visualized **basis vector transformations**
- Studied effects on **distance metrics**
- Applied **matrix transformations** and **feature normalization**
- Improved accuracy **from 76% → 80.9%** using rescaling

**🧠 Key Concepts:** Basis transformation • Normalization • Feature scaling • Correlation

---



**📊 Details:**
- Summarized learning outcomes
- Highlighted role of preprocessing in ML pipeline performance
- Reinforced importance of **data transformation and visualization**

---

## 🧩 Summary Table

| **Lab No.** | **Topic** | **Dataset Used** | **Key Concepts** | **Accuracy Improvement** |
|--------------|------------|------------------|------------------|--------------------------|
| 0 | Probability Primer | Synthetic | Probability, Bayes, Random Variables | — |
| 0.1 | Linear Algebra Fundamentals  | Synthetic | Matrices, Eigenvalues, Transformations | — |
| 1 | Feature Extraction & Visualization | MNIST | Feature selection, visualization | — |
| 2 | Metrics & Evaluation | California Housing | Cross-validation, metrics | — |
| 3 | Data Augmentation | MNIST | Rotation, shear, diversity | +3.8% |
| 4 | Linear Algebra Transformations | MNIST | Basis transform, normalization | +4.9% |

---



## 🧠 Core Languages & Environments

| **Category** | **Tools / Frameworks** | **Purpose** |
|---------------|------------------------|--------------|
| **Language** | Python 3.9+ | Core programming language for all labs |
| **IDE / Platform** | Google Colab / Jupyter Notebook | Interactive coding, visualization, and experimentation |
| **Version Control** | Git & GitHub | Code management, version tracking, and collaboration |

---

## 🔬 Machine Learning & Data Science Libraries

| **Library** | **Purpose / Use Case** |
|--------------|------------------------|
| **NumPy** | Matrix operations, numerical computations, and array manipulation |
| **pandas** | (Optional) Data handling, tabular operations, and preprocessing |
| **scikit-learn** | Machine learning algorithms, metrics, and preprocessing utilities |
| **Keras** | Access to the MNIST dataset and deep learning extensions |
| **scikit-image** | Image transformations (rotation, shear, scaling) for augmentation |
| **Matplotlib** | Plotting and 2D data visualization |
| **Seaborn** | Statistical visualization and aesthetic plots |

---


## 📦 Installation Guide

Install all dependencies at once using pip:

```bash
pip install numpy matplotlib scikit-learn scikit-image keras seaborn
```
---

## 👩‍💻 Author & Credits

**Author:** [Syed Asma](https://github.com/SyedAsma25)  
**Program:** IIIT Hyderabad – Student Training Program (STP)  
**Module:** Artificial Intelligence & Machine Learning – Module 1  
**Created Using:** Google Colab  
**License:** MIT  

---




<p align="center">
 💡 <b>"Transform data wisely, visualize results clearly, and learn continuously."</b>
</p>
