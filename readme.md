**I have designed an Ann model, trained it with churn dataset and using that model predicted whether the customer will stay or leave the company , it has three parts model training , model prediction and using streamlit for visualization and deployment , give me readme file with the above information and also include my tech stack , also provide author details**
#📊 Customer Churn Prediction using ANN

## 📌 Project Overview

This project focuses on predicting **customer churn** (whether a customer will stay with or leave a company) using an **Artificial Neural Network (ANN)**.
The solution is built in **three major parts**:

1. **Model Training**
2. **Model Prediction**
3. **Deployment using Streamlit**

The trained ANN model analyzes customer-related features from a churn dataset and predicts the likelihood of churn, helping businesses take proactive retention measures.

## 🧠 Project Structure

### 🔹 Part 1: Model Training

* Data preprocessing (handling categorical variables, scaling features)
* Feature engineering
* ANN model creation using a neural network
* Model training and evaluation
* Saving the trained model for reuse

### 🔹 Part 2: Model Prediction

* Loading the trained ANN model
* Accepting new customer input data
* Applying the same preprocessing steps
* Predicting whether the customer will:

  * **Stay with the company**
  * **Leave the company (Churn)**

### 🔹 Part 3: Deployment using Streamlit

* Interactive web interface built with Streamlit
* User-friendly input fields for customer data
* Real-time churn prediction
* Deployed ML model integrated with the frontend

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries & Frameworks:**

  * NumPy
  * Pandas
  * Scikit-learn
  * TensorFlow / Keras (ANN Model)
  * Matplotlib / Seaborn (EDA & Visualization)
* **Model Deployment:** Streamlit
* **Dataset:** Customer Churn Dataset

---

## 🚀 How to Run the Project

1. **Clone the repository**

   ```bash
   git clone <repository-link>
   cd customer-churn-ann
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**

   ```bash
   streamlit run app.py
   ```

4. **Open the browser**

   * Navigate to `http://localhost:8501`

---

## 📈 Output

* Predicts **Customer Will Stay** or **Customer Will Leave**
* Provides fast and accurate predictions using ANN
* Interactive UI for real-world usability

---

## 🎯 Use Cases

* Telecom customer churn analysis
* Subscription-based services
* Banking and financial services
* SaaS customer retention strategies

---

## 👤 Author

Name: ARNAB PARIRA Role: Machine Learning / Data Science Enthusiast Project Type: Academic / Learning / Portfolio Project

⭐ Acknowledgement

Thanks to open-source datasets and libraries that made this project possible.

🚀 Connect With Me

📧 Email: arnabparira4@gmail.com Thanks for checking out this project!

✅ Conclusion

This project demonstrates an end-to-end **machine learning workflow**, from training an ANN model to deploying it using Streamlit. It provides a practical solution for customer churn prediction and showcases skills in deep learning, data preprocessing, and model deployment.

This project is for educational purposes only.

If this project helped you, feel free to ⭐ star the repo and share it with others learning.




