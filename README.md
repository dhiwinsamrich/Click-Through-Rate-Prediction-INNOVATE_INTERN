<h1 align=center>🚀 Click-Through Rate Prediction - INNOVATE INTERN 🚀</h1>

<p align=center>Welcome to the **Click-Through Rate (CTR) Prediction** project repository! This project is a comprehensive analysis and implementation of various machine learning models to predict the click-through rate, executed during my internship at **INNOVATE INTERN**. </p>

<p align="center">
  <a href="https://github.com/dhiwinsamrich/Click-Through-Rate-Prediction-INNOVATE_INTERN.git">
    <img src="https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3.9+-brightgreen?style=for-the-badge&logo=python" alt="Python">
  </a>
</p>

![Innovate Intern](https://github.com/user-attachments/assets/8fe7cb15-b12c-4ccb-a1ee-7ecd706a8315)

## 🌟 Overview

Click-through rate prediction is a critical task for improving the performance of online advertisements. This project aims to explore different machine learning models, compare their performance, and implement the best model to predict CTR effectively.

## 📂 Repository Contents

### 1. 📊 All Model Comparison

This file includes a detailed comparison of several machine learning models. We evaluated each model based on key performance metrics such as Accuracy, AUC, Recall, Precision, F1 Score, Kappa, MCC, and Training Time. The models compared are:

- **XGBoost**: Extreme Gradient Boosting
- **LightGBM**: Light Gradient Boosting Machine
- **CatBoost**: CatBoost Classifier
- **Random Forest**: Random Forest Classifier
- **Extra Trees**: Extra Trees Classifier
- **Gradient Boosting**: Gradient Boosting Classifier
- **KNN**: K Neighbors Classifier
- **AdaBoost**: Ada Boost Classifier
- **Logistic Regression**: Logistic Regression
- **LDA**: Linear Discriminant Analysis
- **Decision Tree**: Decision Tree Classifier
- **Naive Bayes**: Naive Bayes
- **Dummy Classifier**: Dummy Classifier
- **QDA**: Quadratic Discriminant Analysis
- **SVM**: SVM with Linear Kernel
- **Ridge Classifier**: Ridge Classifier

#### Model Comparison Results

| Model           | Accuracy | AUC   | Recall | Precision | F1    | Kappa | MCC   | TT (Sec) |
|-----------------|----------|-------|--------|-----------|-------|-------|-------|----------|
| XGBoost         | 0.8690   | 0.9408| 0.8675 | 0.8665    | 0.8668| 0.7379| 0.7383| 23.3160  |
| LightGBM        | 0.8701   | 0.9401| 0.8667 | 0.8690    | 0.8677| 0.7402| 0.7404| 0.2070   |
| CatBoost        | 0.8684   | 0.9391| 0.8560 | 0.8738    | 0.8647| 0.7366| 0.7370| 3.6480   |
| Random Forest   | 0.8546   | 0.9309| 0.8420 | 0.8595    | 0.8506| 0.7091| 0.7094| 0.6700   |
| Extra Trees     | 0.8616   | 0.9298| 0.8570 | 0.8608    | 0.8588| 0.7231| 0.7233| 0.5810   |
| Gradient Boosting| 0.8209  | 0.9031| 0.7843 | 0.8406    | 0.8114| 0.6412| 0.6428| 0.6510   |
| KNN             | 0.7981   | 0.8736| 0.7710 | 0.8091    | 0.7895| 0.5958| 0.5966| 0.4510   |
| AdaBoost        | 0.7847   | 0.8606| 0.7362 | 0.8088    | 0.7706| 0.5687| 0.5711| 0.2110   |
| Logistic Regression| 0.7502| 0.8131| 0.7255 | 0.7567    | 0.7406| 0.5000| 0.5007| 0.4530   |
| LDA             | 0.7511   | 0.8127| 0.7245 | 0.7587    | 0.7410| 0.5017| 0.5025| 0.0530   |
| Decision Tree   | 0.7839   | 0.7839| 0.7833 | 0.7787    | 0.7807| 0.5677| 0.5681| 0.0500   |
| Naive Bayes     | 0.6404   | 0.7031| 0.6611 | 0.6272    | 0.6435| 0.2812| 0.2818| 0.0280   |
| Dummy Classifier| 0.5086   | 0.5000| 0.0000 | 0.0000    | 0.0000| 0.0000| 0.0000| 0.0200   |
| QDA             | 0.4807   | 0.4808| 0.5208 | 0.4697    | 0.4889|-0.0372|-0.0373| 0.0350   |
| SVM             | 0.7438   | 0.0000| 0.7237 | 0.7516    | 0.7340| 0.4871| 0.4911| 0.0590   |
| Ridge Classifier| 0.7511   | 0.0000| 0.7247 | 0.7586    | 0.7411| 0.5017| 0.5025| 0.0260   |

### 2. 🌟 Light Gradient Boosting Model

After a comprehensive analysis, the Light Gradient Boosting Machine (LightGBM) was chosen as the best performing model. This file includes the implementation of the LightGBM model to predict CTR.

## ✨ Features

- **🔍 Model Comparison**: Compare multiple machine learning models on various performance metrics.
- **🚀 LightGBM Implementation**: Efficient and scalable LightGBM model for accurate CTR prediction.
- **📈 Performance Metrics**: Detailed evaluation of models using Accuracy, AUC, Recall, Precision, F1 Score, Kappa, MCC, and Training Time.
- **📊 Visualization**: Graphical representation of model performances for better insights.

## 🛠️ Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/Click-Through-Rate-Prediction-INNOVATE_INTERN.git
cd Click-Through-Rate-Prediction-INNOVATE_INTERN
pip install -r requirements.txt
```

## 🚀 Usage

1. **📊 Model Comparison**:
   - Explore the `All_Model_Comparison.ipynb` file to see the performance comparison of different models.
   
2. **🌟 LightGBM Implementation**:
   - Check out the `Light_Gradient_Boosting.ipynb` file for the implementation and analysis of the LightGBM model.

## 📈 Results

The Light Gradient Boosting Machine (LightGBM) emerged as the best model with an accuracy of 87.01%, AUC of 0.9401, and an impressively low training time of 0.207 seconds. This makes it a robust and efficient choice for CTR prediction.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

Special thanks to **INNOVATE INTERN** for providing the opportunity and resources to work on this project.
