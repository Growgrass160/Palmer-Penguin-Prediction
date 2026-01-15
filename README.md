# 🐧 Penguin Species Prediction App

This project is a machine-learning powered web application that predicts the species of a **Palmer Penguin** based on its physical characteristics and habitat information. The system combines a trained classification model with an interactive web interface, allowing users to explore how different features influence species prediction in real time.

---

## 🚀 What This Project Does

The application allows users to input penguin characteristics such as:

- Island  
- Sex  
- Bill length and depth  
- Flipper length  
- Body mass  

Using these inputs, the system predicts which of the three Palmer penguin species the penguin belongs to:

- **Adelie**  
- **Chinstrap**  
- **Gentoo**

Along with the prediction, the app also displays the **probability** for each species, providing insight into the model’s confidence.

---

## 🧠 How It Works

The project uses a **Random Forest classifier** trained on the Palmer Penguins dataset.

### Model Training
- The dataset is cleaned and categorical features (`sex` and `island`) are encoded using **one-hot encoding**  
- The target variable (`species`) is mapped to numerical labels  
- A **Random Forest classifier** is trained on the processed dataset  
- The trained model is saved using **pickle** for later use in the web app  

### Prediction Pipeline
- User input is collected through a Streamlit sidebar  
- The input is combined with the original dataset to ensure consistent encoding  
- One-hot encoding is applied to match the model’s training format  
- The trained model is loaded and used to generate:
  - A species prediction  
  - Probability scores for each class  

---

## 🔥 Key Features

- Real-time penguin species prediction  
- Uses a trained **Random Forest** model  
- Automatic encoding of categorical features  
- Displays prediction probabilities  
- Simple and intuitive web interface  
- Fully reproducible machine learning pipeline  

---

## 🛠 Technology Stack

- **Python** – data processing and model logic  
- **Pandas & NumPy** – data handling  
- **Scikit-learn** – Random Forest classification  
- **Streamlit** – interactive web application  
- **Pickle** – model serialization  

---

## 🎯 Why This Project Matters

This project demonstrates an end-to-end machine learning workflow:

- Data preprocessing  
- Feature encoding  
- Model training  
- Model persistence  
- Deployment as an interactive web app  

Rather than being just a notebook-based model, this project turns a trained ML classifier into a **usable product**, allowing users to experiment with real-world data and instantly see predictions.

---

## 📊 Dataset

The model is trained on the **Palmer Penguins dataset**, a popular real-world dataset used for classification and exploratory data analysis in machine learning.

---

If you want, I can also help you add:
- installation instructions  
- how to run locally  
- or a screenshot/demo section so it looks even more polished on GitHub 🚀

