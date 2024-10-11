# 🚀 GST Analytics Hackathon Project

Welcome to my project repository for the **GST Analytics Hackathon**! 🎉 This repository contains all the code, documentation, and resources used to develop a predictive model aimed at solving a complex binary classification problem within the GST system.

## 📁 Repository Structure

- **`docs/`**: Contains the supporting documentation for this project.
- **`models/`**: Contains model pickle files.
- **`main.ipynb/`**: The source code for this project.
- **`README.md`**: This file, providing an overview of the project.

## 📊 Project Overview

- **Objective**: To create a machine learning model that predicts whether a specific entity is classified as "0" or "1" based on various attributes provided in the dataset.
- **Dataset**: The project uses a dataset containing 900,000 records with 21 attributes, including anonymized and labeled data.
- **Methodology**: This involves data preprocessing, training different models, and evaluating them based on Accuracy, Precision, Recall, F1 Score, AUC-ROC, Log Loss and Balanced Accuracy.
- **Tools & Technologies**: 
  - Python
  - Visual Studio Code
  - scikit-learn, XGBoost, LightGBM, etc.
  - Pandas and NumPy for data manipulation
  - Matplotlib and seaborn for visualization
  - SMOTE for upsampling
  - Optuna for hyperparameter tuning

## 🔍 Key Features

- **Model Performance**: Evaluated using various metrics Accuracy, Precision, Recall, F1 Score, AUC-ROC, Log Loss, Balanced Accuracy, Classification Report and Confusion Matrix.
- **Innovative Approach**: Incorporates advanced techniques like bayesian hyperparameter tuning, data upsampling and model ensemble to boost performance.
- **Reproducibility**: All steps are documented and reproducible, ensuring that results can be verified by others.

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/S84v/gst-analytics-hackathon.git
   cd gst-analytics-hackathon
   ```
2. **Set up the environment:**
    a. Install Python 3.x.

    b. Install the following packages:

    1. Pandas
    2. NumPy
    3. Matplotlib
    4. seaborn
    5. imbalanced-learn
    6. sk-learn
    7. XGBoost
    8. LightGBM
    9. Optuna
    10. joblib

    c. Create a subdirectory **`data/`** and copy the following files into it:
    1. X_Test_Data_Input.csv
    2. X_Train_Data_Input.csv
    3. Y_Test_Data_Target.csv
    4. Y_Train_Data_Target.csv

3. **Run the Jupyter notebooks:**

    1. Open the `main.ipynb` file to explore the source code.
    2. Run all cells of the notebook (ensure all the dependencies are installed first).
    3. After the notebook has finished running, it will create 4 models in the **`models/`** directory.
    4. **The best performing model is `VotingClassifier`. Ensure to validate new data against this model for the best performance.**

4. **Examine the visualizations:**

     Examine the visualizations in the `main.ipynb` file for insights about individual model's performance.

## 🌟 Why This Project Matters
This project is a crucial step towards improving the GST system in India by developing a model that can accurately predict key outcomes. The solution not only demonstrates my technical proficiency but also has potential real-world applications that can streamline tax administration.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📧 Contact
For any questions or inquiries, please reach out via 
1. [LinkedIn](https://www.linkedin.com/in/sarang-dave/) 
2. [GitHub](https://github.com/S84v)
3. Email-ID: [davesarang08@gmail.com](mailto:davesarang08@gmail.com)
4. Phone Number: +91 9082783721
