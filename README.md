# Machine Learning Lab (ML-TP) – 24CS03TH0501

**Name:** Soumya Jaiswal &nbsp;|&nbsp; **Section:** B &nbsp;|&nbsp; **Batch:** B1 &nbsp;|&nbsp; **Roll No:** 10

| Lab | Aim | Folder |
|-----|-----|--------|
| Lab 5 | To implement K-Nearest Neighbor (KNN) algorithm for Classification and Regression | [Lab-5_KNN](Lab-5_KNN) |
| Lab 6 | To implement the Perceptron Learning Algorithm | [Lab-6_Perceptron](Lab-6_Perceptron) |
| Lab 7 | To implement the Naïve Bayes Classification algorithm using a suitable dataset | [Lab-7_Naive_Bayes](Lab-7_Naive_Bayes) |
| Lab 8 | To implement the Support Vector Machine (SVM) classification algorithm using a suitable dataset | [Lab-8_SVM](Lab-8_SVM) |

Each folder contains the Jupyter notebook (with outputs) and the dataset it uses.

## Datasets
- **Lab 5:** Pima Indians Diabetes dataset (`diabetes.csv`) for classification; scikit-learn `load_diabetes()` for regression.
- **Lab 6:** UCI Seeds dataset (`seeds_new.csv`) – 210 wheat kernels, 7 features, 3 classes.
- **Lab 7:** UCI Raisin dataset (`Raisin_Dataset.xlsx`) – 900 raisins, 7 features, 2 classes (Kecimen, Besni).
- **Lab 8:** UCI AI4I 2020 Predictive Maintenance dataset (`ai.csv`) – 10,000 machines, product type and 5 sensor features, 2 classes (failure, no failure).

## How to run
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow openpyxl notebook
```
Open a notebook from inside its folder (so the dataset path resolves) and run all cells.
The last cell of Lab 7 asks for the measurements of a new raisin using `input()`.
