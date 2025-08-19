README.txt
===========

ANN for Medical Diagnosis
============================================

This project implements neural network models to classify three UCI medical datasets:
1. Heart Disease Classification
2. Diabetes Prediction (Pima Indians)
3. Breast Cancer Detection (Wisconsin Dataset)

Each model is built using TensorFlow and trained on cleaned and preprocessed data, achieving strong performance metrics.

All the datasets are from UCI machine learning repository and Kaggle.

-----------------------------------------------------
SETUP
-----------------------------------------------------

1. Download the project files to your local system.

2. Ensure you have Python 3.7 or later installed.

3. Create a virtual environment (recommended):

   For Windows:
   > python -m venv venv
   > venv\Scripts\activate

   For Linux/macOS:
   $ python3 -m venv venv
   $ source venv/bin/activate

4. Install required libraries:
   
   $ pip install numpy pandas matplotlib seaborn scikit-learn tensorflow

-----------------------------------------------------
EXECUTION
-----------------------------------------------------

Each classification task is in a separate script (e.g., `heart_disease.ipynb`, `diabetes.ipynb`, `breast_cancer.ipynb`).
To run the models:

1. **Heart Disease Classification**
   $ python heart_disease.ipynb

2. **Diabetes Prediction**
   $ python diabetes.ipynb

3. **Breast Cancer Detection**
   $ python breast_cancer.ipynb

Each script performs:
- Dataset loading
- Data cleaning and preprocessing
- Exploratory data analysis.
- Model creation and training
- Evaluation of performance (accuracy, recall, etc.)
- Plotting of training/validation losses (if applicable)

Note:
- Models include early stopping to avoid overfitting.
- Performance may vary slightly due to random initialization during training.

-----------------------------------------------------
LIBRARIES USED
-----------------------------------------------------

- **TensorFlow**: For building and training neural networks
- **NumPy**: Numerical computations
- **Pandas**: Data manipulation and preprocessing
- **Matplotlib**: Plotting performance metrics 
- **Scikit-learn**: Data scaling, encoding, splitting, and evaluation metrics



-----------------------------------------------------

