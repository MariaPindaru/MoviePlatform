
# Movie Rating Platform

This project offers a platform for movie recommendations, search, and ratings, utilizing advanced machine learning models and modern web technologies.

## Table of Contents

- [Introduction](#introduction)
- [Components](#components)
  - [Movie Recommender](#movie-recommender)
  - [Chatbot Recommender](#chatbot-recommender)
  - [Movie Search](#movie-search)
- [Technologies](#technologies)
  - [Backend](#backend)
  - [Frontend](#frontend)
- [License](#license)

## Introduction

This platform provides users with personalized movie recommendations, an interactive chatbot for recommendations, and a search feature based on movie descriptions. It leverages a combination of neural networks, hybrid recommenders, and natural language processing techniques to deliver an engaging user experience.

![image](https://github.com/user-attachments/assets/294ff717-852a-45aa-b70b-9dfebcde7b26)

## Components

### Movie Recommender

- **Neural Network (Behavior Sequence Transformer)**: Utilizes a transformer-based neural network to recommend movies based on user behavior sequences. (Q. Chen, Z. Huan , L. Wei, H. Pipei și O. Wenwu , „Behavior sequence transformer for 
e-commerce recommendation in Alibaba”, 2019)
- **Hybrid Recommender**: Combines content-based filtering and collaborative filtering to enhance recommendation accuracy.
![image](https://github.com/user-attachments/assets/9fd1e73b-82e5-49b5-93c7-dc8089d9e54e)
### Chatbot Recommender

- **Classifier (LSTM)**: Uses a Long Short-Term Memory (LSTM) network to classify user inputs and provide movie recommendations.
- **Recommendation Criteria**:
  - Random movie
  - Genre-specific recommendations
  - Director-specific recommendations
  - Similarity with another movie
![image](https://github.com/user-attachments/assets/ade557d3-4591-4825-b802-1295a901ffc4)

### Movie Search

- **Description-Based Search**: Implements TF-IDF encoding combined with a Nearest Neighbor algorithm to allow users to search for movies based on descriptions.
![image](https://github.com/user-attachments/assets/522d171a-3995-427d-8ed0-efea718416dd)
## Technologies

### Backend

- **Flask**: A lightweight WSGI web application framework for Python.
- **Firebase Authentication + JSON Web Token (JWT)**: Handles user authentication securely.
- **Firebase Firestore**: A flexible, scalable database for storing user data and movie information.
- **TensorFlow**: An open-source machine learning framework for developing and training models.
- **Scikit-learn**: A library for machine learning in Python, used for implementing various algorithms.

### Frontend

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A build tool that provides a faster and leaner development experience for modern web projects.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
