Heart Disease Prediction Model Using Machine Learning

ABSTRACT- Technology and medical science have developed quite a lot in last few decades and their combination has made a vital
role in developing medicines and machines to help doctors in various diseases, sometimes these diseases are harder to predict and
the delays could be fatal. If there is a way so that we can shortlist people who may have a particular disease it can significantly
reduce the burden from the medical industry and can be a game changer. Currently we have a lot of machine learning algorithms
that can help us in determining patterns that could lead to a disease. In Our findings we used different machine learning technics
and algorithms like neural network, SVM, decision tree etc. to find whether an individual has Chronical Heart Disease or not. After
comparison of results with other researches and correctly using the resources, methods , technique and technology we concluded
everything in our results and findings where SVM had the best accuracy and others performed fairly.


Welcome to the Heart Disease Prediction Model repository! This project leverages machine learning to predict heart disease using various health parameters. The repository contains machine learning code for building and training the model, as well as HTML, CSS, and JavaScript code for the web interface.

This repo contains the Final Project Report, Dataset which is picked from Cleaveland University, Plag Report, Research paper as well as certificates of research paper presentation at HMRITM ICAMC - 2024.            

The Heart Disease Prediction Model uses a machine learning algorithm to predict the likelihood of heart disease in individuals based on input health parameters. The web interface allows users to enter their data and view the prediction results.

Project Requirements:
To run this project, you need the following tools and libraries:

Python 3.x
Jupyter Notebook or any Python IDE

Libraries:
pandas
numpy
scikit-learn
matplotlib
A web browser

The frontend part requires basic web development knowledge and tools:

HTML
CSS
JavaScript
Installation
Follow these steps to set up the project on your local machine:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
Set up the Python environment:
Ensure you have Python installed. Then, create a virtual environment and activate it:

bash
Copy code
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
Install the required Python libraries:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook
Open the notebook file (Heart_Disease_Prediction_Model.ipynb) and run all cells to train the model and save it.

Usage:
Running the Machine Learning Code
Train the model:
Open the Heart_Disease_Prediction_Model.ipynb notebook in Jupyter Notebook. Run all the cells to train the model. This will also save the trained model to a file (model.pkl).

Predict using the model:
Use the trained model to make predictions by providing new input data. You can test this in the notebook or create a new script to load the model and predict.

Running the Web Interface
Open the HTML file:
Navigate to the web directory and open index.html in your web browser. This file contains the web interface for inputting data and viewing predictions.

Input data and view results:
Enter the required health parameters into the form on the webpage and click the "Predict" button to view the prediction results.

