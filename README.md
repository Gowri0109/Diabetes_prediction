# Diabetes_prediction</br>

**Overview**

This repository contains a Diabetes Prediction project that utilizes Machine Learning to predict the likelihood of diabetes based on input health parameters. The model is trained on a dataset containing various medical attributes and applies classification techniques to determine the presence of diabetes.

**Features**

- Data preprocessing and feature selection</br>
- Implementation of machine learning algorithms for classification</br>
- Model evaluation and performance metrics</br>
- Web application interface for predictions (if applicable)</br>

**Dataset**
The dataset used in this project contains medical parameters such as:</br>
- Age</br>
- BMI (Body Mass Index)</br>
- Blood pressure</br>
- Glucose levels</br>
- Insulin levels</br>
- Skin thickness</br>
- Diabetes pedigree function

**Technologies Used**
Programming Language: **Python**

**Libraries:**
- NumPy</br>
- Pandas</br>
- Scikit-Learn</br>
- Matplotlib</br>
- Seaborn</br>
- Flask (if a web interface is included)</br>
- Jupyter Notebook for model training and evaluation


**Installation**

To run this project locally, follow these steps:

**Clone the repository:**

```git clone https://github.com/Gowri0109/Diabetes_prediction.git```

**Navigate to the project directory:**

```
cd Diabetes_prediction
```
**Create a virtual environment (optional but recommended):**

```python
python -m venv venv
source venv/bin/activate  # For MacOS/Linux</br>
venv\Scripts\activate  # For Windows
```
<\br>

**Install dependencies:**

```python
pip install -r requirements.txt
```
Run the Jupyter Notebook for model training and evaluation:

jupyter notebook

**Usage**

Run the notebook to train and evaluate the model.

If a web interface is implemented, start the Flask app with:

```python 
app.py
```
Input the required parameters and get predictions for diabetes.


**Model Performance**
The model performance is evaluated using:
- Accuracy Score</br>
- Confusion Matrix</br>
- Precision, Recall, and F1-score</br>
- ROC Curve and AUC Score</br>


**Contributions**
Contributions are welcome! If you wish to contribute:
- Fork the repository
- Create a new branch (feature-branch)
- Make necessary modifications
- Commit and push changes
- Open a pull request

