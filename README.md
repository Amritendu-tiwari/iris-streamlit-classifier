# 🌸 Iris Species Classifier with Streamlit

This project is a simple web application built using **Streamlit** that classifies iris flowers into different species based on their features using a **Random Forest Classifier**.

## 🚀 Features

- Interactive UI with Streamlit
- User input sliders for Sepal and Petal dimensions
- Predicts Iris species: *Setosa*, *Versicolor*, or *Virginica*
- Real-time machine learning predictions
- Uses scikit-learn’s built-in Iris dataset

## 🧠 Technologies Used

- Python
- Streamlit
- Pandas
- scikit-learn (RandomForestClassifier)

## 🔧 How it Works

1. **Data Loading**: The Iris dataset is loaded using `sklearn.datasets.load_iris()`.
2. **Model Training**: A RandomForestClassifier is trained on the dataset.
3. **User Inputs**: Users input flower measurements using Streamlit sliders.
4. **Prediction**: The trained model predicts the species of the flower.
5. **Output**: The result is displayed on the webpage.

## 🛠 Installation & Running

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/iris-streamlit-classifier.git
cd iris-streamlit-classifier
