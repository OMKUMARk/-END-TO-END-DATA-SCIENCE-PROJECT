END-TO-END DATA SCIENCE PROJECT

company: CODTECH IT SOLUTIONS

NAME: OM KUMAR

INTERN ID: CT04DH1971

DOMAIN: DATA SCIENCE

DURATION: 4 WEEKS

MENTOR: Muzammil

Iris Flower Classifier: End-to-End Data Science Project
This project is a complete end-to-end data science pipeline built during my internship at CODTECH as part of Task 3. The goal of the project is to develop a machine learning model that can accurately classify the species of an Iris flower based on four key measurements: sepal length, sepal width, petal length, and petal width. The final solution is deployed as a functional web application using Flask, where users can input measurements and receive real-time predictions.

1. Problem Statement
Iris flowers belong to three distinct species: Setosa, Versicolor, and Virginica. While these species can be visually similar, machine learning can help classify them based on numerical features. The project aims to build a robust ML model to distinguish between these species and make the solution accessible through a web interface.

2. Tools and Technologies Used
Python: Core programming language

Scikit-learn: For data preprocessing and machine learning

Pandas & NumPy: For data manipulation

Matplotlib & Seaborn: For data visualization

Flask: For building and deploying the web application

HTML/CSS: For the frontend of the application

3. Workflow
Data Collection and Exploration
The Iris dataset is loaded using scikit-learn. It contains 150 samples with 4 numeric features. The data is analyzed for patterns, correlations, and class distributions using visualizations like scatter plots.

Preprocessing and Model Training
The dataset is split into training and test sets. A Random Forest Classifier is trained on the training data. This model was chosen for its simplicity, speed, and ability to handle multi-class classification tasks well. Once trained, the model is saved using Python’s pickle library so it can be reused during deployment.

Web Deployment Using Flask
A simple yet functional web app is created using Flask. The app consists of:

An HTML form where users can input the four flower measurements

A backend (app.py) that loads the trained model and processes user input

A prediction system that displays the predicted flower species on the same page

User Experience
The app is easy to use. A user enters the required measurements and clicks "Predict." The app then processes the data and returns the predicted Iris species almost instantly.

4. Output and Visualization
The project also includes a sample output image that visualizes how different species cluster based on sepal and petal length. This helps demonstrate the model’s capability to differentiate between species visually.

5. Outcome and Learning
By completing this task, I gained practical experience in working through the entire data science pipeline — from collecting and exploring data to deploying a model as a live web application. This project helped me understand the importance of clean code, modular workflow, and user-friendly design in real-world applications.

6. Future Improvements
Adding error handling and validation for input fields

Allowing API access via JSON for programmatic usage

Deploying the app on a live server (e.g., Heroku or Render)

#OUTPUT#

<img width="1600" height="1200" alt="Image" src="https://github.com/user-attachments/assets/37e9be7f-9788-4cac-9617-339ad1f10df5" />
