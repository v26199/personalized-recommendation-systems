# Movie Recommender System

## Introduction

The Movie Recommender System is designed to provide personalized movie recommendations using advanced machine learning and Natural Language Processing (NLP) techniques. This project leverages multiple recommendation approaches to enhance user experience by suggesting movies tailored to individual preferences.

## Technologies Used

- **Recommendation Techniques**:
  - **Content-Based Filtering**: Recommends movies based on the features and attributes of the movies the user has previously liked.
  - **Collaborative Filtering**: Suggests movies based on user behavior and preferences, identifying patterns from similar users.
  - **Hybrid Approach**: Combines both content-based and collaborative filtering techniques for improved recommendation accuracy.

- **Machine Learning and NLP**: Utilized for model training, feature extraction, and data processing.

- **Web Technologies**:
  - **Flask**: Used to develop the web application for interactive user interfaces.
  - **HTML/CSS/JavaScript**: Employed for frontend development, creating a user-friendly experience.
  - **Bootstrap**: For responsive design and UI enhancements.

## Data Collection

- **Data Source**: Scraped movie data from the online IMDB site using its API.
- **Data Extraction**: Extracted movie information, including ratings, genres, and descriptions, to build a comprehensive dataset for training the recommendation models.

## Performance

- **Model Accuracy**: Achieved an F1 score of 82%, indicating high precision and recall in movie recommendations.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/v26199/personalized-recommendation-systems.git
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask App**:
   ```bash
   python app.py
   ```

4. **Access the Web Application**: Open your browser and go to `http://localhost:5000` to start using the movie recommender system.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the creators of the IMDB API and the various libraries and frameworks that made this project possible.
