# Fake News Detection using Machine Learning

## 📌 Project Overview

Fake News Detection is a Natural Language Processing (NLP) and Machine Learning project that classifies news articles as **Fake** or **Real** based on their textual content.

The project applies text preprocessing and **TF-IDF (Term Frequency–Inverse Document Frequency)** to convert news text into numerical features. Machine Learning classification algorithms are then trained to identify patterns in the text and predict whether a news article is fake or real.

## 🎯 Objective

The main objective of this project is to build a machine learning model that can automatically classify news articles into:

* **Fake News**
* **Real News**

This project demonstrates the use of NLP techniques for a real-world text classification problem.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Natural Language Processing (NLP)**
* **TF-IDF Vectorization**
* **Logistic Regression**
* **Support Vector Machine (SVM)**
* **Jupyter Notebook**

## 🔄 Project Workflow

```text
News Dataset
     ↓
Data Loading
     ↓
Data Cleaning & Preprocessing
     ↓
Text Feature Extraction
     ↓
TF-IDF Vectorization
     ↓
Train/Test Split
     ↓
Machine Learning Model
     ↓
Model Evaluation
     ↓
Fake / Real Prediction
```

## 🔍 Methodology

### 1. Data Loading

The news dataset is loaded using Pandas and inspected to understand its structure, features, and target labels.

### 2. Data Preprocessing

The textual data is prepared for machine learning by performing the required cleaning and preprocessing steps.

### 3. TF-IDF Vectorization

TF-IDF is used to convert the news text into numerical feature vectors.

TF-IDF gives higher importance to words that are useful for distinguishing documents while reducing the importance of very common words.

### 4. Model Training

Machine Learning classification algorithms are trained using the extracted TF-IDF features.

The project experiments with classification models such as:

* Logistic Regression
* Support Vector Machine (SVM)

### 5. Prediction

The trained model can classify a news article based on its textual content and predict whether it is **Fake** or **Real**.

### 6. Evaluation

The trained models are evaluated using appropriate classification metrics to understand their performance on unseen data.

## 📊 Results

The project demonstrates that traditional Machine Learning and NLP techniques such as **TF-IDF combined with classification algorithms** can be used effectively for fake news classification.

The notebook contains the model training, predictions, and evaluation results.

## 📂 Project Structure

```text
Fake-News-Detection/
│
├── Fake_News_Detection.ipynb
├── .gitignore
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Khedkarvm/fake-news-detection-using-machine-learning.git
```

### 2. Open the project

```bash
cd fake-news-detection-using-machine-learning
```

### 3. Open the notebook

Open:

```text
Fake_News_Detection.ipynb
```

using Jupyter Notebook or JupyterLab.

### 4. Run the cells

Run the notebook cells sequentially to perform preprocessing, feature extraction, model training, evaluation, and prediction.

## 💡 Key Learning

Through this project, I gained practical experience in:

* Natural Language Processing
* Text preprocessing
* TF-IDF feature extraction
* Machine Learning classification
* Model evaluation
* Working with real-world text data
* Building an end-to-end NLP classification workflow

## 🚀 Future Improvements

Possible improvements include:

* Trying advanced NLP techniques such as word embeddings
* Using Deep Learning models
* Comparing additional classification algorithms
* Hyperparameter tuning
* Building a simple web interface for real-time prediction
* Deploying the model as an API or web application

## 👩‍💻 Author

**Vaishnavi Khedkar**

Master's in Industrial Mathematics with Computer Applications

Interested in **Data Science, AI/ML, and Generative AI**.
