# Flask Chatbot Application

## Overview

This is a Flask-based chatbot application that utilizes machine learning to provide automated responses to frequently asked questions in an e-commerce context. The chatbot is powered by a Support Vector Machine (SVM) model trained on a dataset of questions and answers. The application also includes user registration and authentication using MongoDB.

## Features

- **Machine Learning Model**: Utilizes a TF-IDF vectorizer and SVM classifier to generate responses based on user input.
- ![Screenshot (360)](https://github.com/user-attachments/assets/265a8b5d-bc7f-43b1-862e-fdd21436285e)

- **User Registration**: Allows users to register and store their credentials securely in MongoDB.
- ![Screenshot (365)](https://github.com/user-attachments/assets/53913f62-acda-4933-b58d-70ca45db272f)

- **Login Functionality**: Users can log in to access personalized features.
- ![Screenshot (364)](https://github.com/user-attachments/assets/354788b4-85a8-416d-81e5-b00d63398bbb)

- **Voice Input**: Supports voice input to enhance user interaction (if implemented).
- ![Screenshot (361)](https://github.com/user-attachments/assets/b7f0f9a6-656f-486f-b3e1-b03ba7658b17)

- **Rate Limiting**: Protects against brute-force attacks on the login endpoint.
- ![Screenshot (362)](https://github.com/user-attachments/assets/0b1ddfdf-e8fc-4d18-91b9-0d44077b44ed)


## Technologies Used

- **Backend**: Flask, Flask-PyMongo
- **Machine Learning**: Scikit-learn (SVC, TfidfVectorizer)
- **Database**: MongoDB
- **Security**: Werkzeug (for password hashing)
- **Web Framework**: Flask-Limiter (for rate limiting)

## Installation

### Prerequisites

- Python 3.x
- MongoDB installed and running locally

### Steps to Install

You can access the complete project repository at [E-commerce Chatbot Repository](https://github.com/Samhitha310/E-commerce-chatbot/).

To navigate to the chatbot script, you can use the following command:

```bash
cd path/to/your/repo/chat.py
