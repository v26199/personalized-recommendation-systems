# Personalized Recommendation Systems

This repository contains advanced projects focused on personalized recommendation systems for **book accommodation** and **movie recommendations**. 
The project leverages Natural Language Processing (NLP) and Machine Learning (ML) techniques to provide tailored recommendations based on user interactions, preferences, and content features.

## Features
- **Book Accommodation and Movie Recommendations**: Personalized suggestions for books and movies based on user behaviour, reviews, and content analysis.
- **Multiple Recommendation Approaches**:
  1. **Rating and Review-Based**: Uses sentiment analysis of user reviews and ratings to recommend the highest-rated items.
  2. **Content-Based Filtering**: Recommends items by comparing features like genres, authors, actors, and plot elements.
  3. **Collaborative Filtering**: Utilizes user-item interaction data to recommend items based on similar users’ preferences.
  4. **Hybrid Filtering**: Combines content-based and collaborative methods to improve recommendation accuracy.
- **Web Application**: Built using HTML, CSS, JavaScript for the frontend, and Flask for the backend API.
  
## Setup Instructions

### 1. Clone the Repository
```bash
git clone (https://github.com/v26199/personalized-recommendation-systems/edit/main)
cd personalized-recommendation-systems
```

### 2. Install Dependencies
Make sure you have Python and pip installed. Install required Python libraries:
```bash
pip install -r requirements.txt
```

### 3. Run the Web Application
Start the Flask server by running:
```bash
python app.py
```
The web app will be accessible at `http://localhost:5000`.

### 4. Access the Application
Open your web browser and go to `http://localhost:5000`. You will see the web interface where you can interact with the personalized recommendation system for books and movies.

## Usage
1. **Rating and Review-Based**: Displays top-rated books and movies based on user reviews.
2. **Content-Based**: Suggests books and movies similar to user preferences or previous selections.
3. **Collaborative Filtering**: Recommends items based on patterns found from other users with similar preferences.
4. **Hybrid**: Combines collaborative and content-based filters for more accurate suggestions.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **Machine Learning Models**: Scikit-learn, NLP techniques
- **APIs**: Flask API for seamless interaction between backend and frontend
- **Deployment**: Docker (containerized deployment)

## Future Improvements
- Add more recommendation approaches (e.g., matrix factorization).
- Implement real-time recommendations using streaming data.
- Enhance UI with React.js or Vue.js for dynamic interactions.

