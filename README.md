# sms_spam_detector

This project implements a machine learning model to classify SMS text messages as either "spam" or "ham" (non-spam). The solution uses a Support Vector Classification (SVC) model to make predictions based on the content of the text message. The project is built using Python, and the model is deployed through a Gradio web application for user-friendly interaction.

#Background
In this project, the task is to refactor an SMS text classification solution into a function that constructs and trains a linear SVC model. Once trained, the model is used to classify new SMS messages as spam or not. The Gradio app is created to allow users to input their own text messages and receive real-time feedback based on the model's predictions.

#Features
Model Training: The system uses the SMSSpamCollection dataset to train a linear SVC model. The model is built and trained using the sms_classification function.

Prediction Functionality: A function called sms_prediction is used to classify new incoming text messages, outputting whether the text is "spam" or "ham".

Gradio Interface: A simple Gradio interface allows users to input a text message and get a classification result ("spam" or "ham") based on the trained model.
