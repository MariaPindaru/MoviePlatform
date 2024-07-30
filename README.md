
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
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This platform provides users with personalized movie recommendations, an interactive chatbot for recommendations, and a search feature based on movie descriptions. It leverages a combination of neural networks, hybrid recommenders, and natural language processing techniques to deliver an engaging user experience.

## Components

### Movie Recommender

- **Neural Network (Behavior Sequence Transformer)**: Utilizes a transformer-based neural network to recommend movies based on user behavior sequences.
- **Hybrid Recommender**: Combines content-based filtering and collaborative filtering to enhance recommendation accuracy.

### Chatbot Recommender

- **Classifier (LSTM)**: Uses a Long Short-Term Memory (LSTM) network to classify user inputs and provide movie recommendations.
- **Recommendation Criteria**:
  - Random movie
  - Genre-specific recommendations
  - Director-specific recommendations
  - Similarity with another movie

### Movie Search

- **Description-Based Search**: Implements TF-IDF encoding combined with a Nearest Neighbor algorithm to allow users to search for movies based on descriptions.

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

## Installation

To get started with the project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/movie-rating-platform.git
    cd movie-rating-platform
    ```

2. **Backend Setup**:
    - Create a virtual environment and install dependencies:
        ```bash
        python -m venv venv
        source venv/bin/activate  # On Windows use `venv\Scripts\activate`
        pip install -r requirements.txt
        ```
    - Configure Firebase and environment variables as needed.

3. **Frontend Setup**:
    - Navigate to the `frontend` directory and install dependencies:
        ```bash
        cd frontend
        npm install
        ```

4. **Running the Application**:
    - Start the backend server:
        ```bash
        flask run
        ```
    - Start the frontend development server:
        ```bash
        npm run dev
        ```

## Usage

Once the application is running, you can:

- Access the movie recommendation system via the web interface.
- Interact with the chatbot for personalized movie recommendations.
- Use the search feature to find movies based on descriptions.

## Contributing

We welcome contributions to improve the Movie Rating Platform! To contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a Pull Request on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
