# Machine Learning Projects

This repository contains three separate machine learning projects, each targeting a different prediction task using different algorithms. The datasets are stored in `data/kaggle/`, and the corresponding notebooks are found in the `notebooks/` directory.

## 📁 File Structure

. ├── data │ └── kaggle │ ├── diabetes.csv # Dataset for diabetes prediction │ ├── House Price.csv # Dataset for house price prediction │ └── student-mat.csv # Dataset for student performance prediction ├── notebooks │ ├── diabetics.ipynb # KNN model for diabetes prediction │ ├── house-prediction.ipynb # Simple Linear Regression for house price prediction │ └── student-performanc.ipynb # SVM model for student performance prediction └── Readme.md

## 📊 Projects

### 1. 🏠 House Price Prediction

- **Algorithm**: Simple Linear Regression
- **Notebook**: `house-prediction.ipynb`
- **Dataset**: `House Price.csv`
- **Description**: Predicts house prices based on features like area, location, etc., using a basic regression approach.

### 2. 🧑‍🎓 Student Performance Classification

- **Algorithm**: Support Vector Machine (SVM)
- **Notebook**: `student-performanc.ipynb`
- **Dataset**: `student-mat.csv`
- **Description**: Classifies student performance based on academic and social factors using SVM.

### 3. 🩺 Diabetes Prediction

- **Algorithm**: K-Nearest Neighbors (KNN)
- **Notebook**: `diabetics.ipynb`
- **Dataset**: `diabetes.csv`
- **Description**: Predicts whether a patient is diabetic based on medical attributes using the KNN algorithm.

## 🚀 How to Run

1. Clone the repository.
2. Open the notebooks in Jupyter Notebook or VS Code.
3. Make sure required libraries are installed:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the cells to see the model training, evaluation, and results.

## 🧠 Requirements

The notebooks use the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `imblearn`

---

Feel free to contribute or improve these models!
