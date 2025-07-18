# 💧 Water Quality Prediction Web App

### Introduction

This repository represents the minor project submission for the group of 3 members under the course under the guidance of Dr. Arun Anoop M.

The group members are:

- [KISHORE M]([https://www.linkedin.com/in/KISHORE M/](https://www.linkedin.com/in/kishore-m-3b7853279?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app )

This project is a responsive web application that allows users to input various water quality parameters and receive a prediction indicating whether the water is safe or unsafe.

### 🔍 Prediction Result Page

The **Prediction Result Page** is styled to display the outcome of the water quality prediction model in a clear and modern way.

### 🖥️ Features:
- Visually engaging interface using custom CSS
- Displays the predicted result (e.g., "Safe" or "Unsafe")
- Responsive design for mobile and desktop
- Includes a "Go Back" button for re-entry of values

### 🔧 Technologies Used:
- **HTML5 & CSS3**
- **Flask (Backend Integration Placeholder)**
- **Custom Animations & Styling**

This file helps in presenting a clean output view after the ML model processes user input.
> 🚀 Feel free to clone, customize, and expand this as part of any water-quality monitoring or environmental analytics system.

### Project Overview

This repository contains the final project submission for the Water Quality Prediction. This project employs machine learning to predict water potability, assessing safety through diverse quality indicators. The dataset includes pH, hardness, and chemical concentrations, forming the basis for predictive models. Addressing imbalances, ethical concerns, and feature analysis, the project contributes to proactive water quality management, aiming for global access to clean and safe drinking water.

### Exploratory Data Analysis (EDA)

EDA tasks focus on visualizing missing values, understanding the distribution of potability, exploring relationships between columns, calculating correlations, and creating histograms. These steps collectively provide a comprehensive understanding of the dataset.

### Results

The project employed various machine learning algorithms for classification, including Logistic Regression, Decision Tree Classifier, Random Forest Classifier, K-Nearest Neighbors (KNN), Support Vector Classifier (SVM), Naive Bayes, and XGBoost. SVM stood out for its robust performance, demonstrating superior accuracy and a balanced precision-recall trade-off compared to other models.

### Application Deployment

A demo application was deployed using Flask, offering a simple web form for users to input water quality parameters and receive predictions on water potability. The application's code is hosted on [GitHub](https://github.com/Projects-UNH/Water-Quality-Prediction).

### How to Run the Flask Application

1.**Clone the Repository:**
```python
git clone https://github.com/YourUsername/Water-Quality-Prediction.git
```
2.**Navigate to Project Directory:**
```python
cd Water-Quality-Prediction
```
3.**Install Dependencies:**
```python
pip install -r requirements.txt
```
4. **Run the Flask App:**
Execute the following command to run the Flask application:
```python
python app.py
```

This will start the Flask development server.

5. **Access the Application:**
Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/). You should see the water quality prediction form.

6. **Input Water Quality Parameters:**
Fill in the values for pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity.

7. **Submit the Form:**
Click the "Predict Potability" button to submit the form. The application will process your input and display the prediction results.

8. **Explore Results:**
Review the prediction for water potability (Potable or Not Potable) based on the provided water quality parameters.

That's it! You have successfully run the Flask application and used the machine learning model to predict water potability.


## Conclusion

The Water Quality Prediction project contributes to the intersection of data science and public health by leveraging machine learning techniques to ensure safe drinking water. The results highlight the potential of SVM for accurate water quality classification.


Feel free to explore and contribute to the project, enhancing our understanding of water quality and safety for human consumption.
