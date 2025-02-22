## Movie Recommender System
# Overview
This is a full-stack Movie Recommender System built using Deep Learning, Machine Learning, and Streamlit. It provides personalized movie recommendations based on user preferences, leveraging advanced ML models and a responsive UI.

# Features
Personalized Recommendations: Uses ML algorithms to suggest movies based on similarity.
Interactive UI: Built with Streamlit for a seamless user experience.
Full-Stack Implementation: Includes both frontend and backend components.
Pre-trained Model: Uses a trained deep learning model for recommendation.

# Technologies Used
Python: Backend development
Streamlit: Web interface
Pandas & NumPy: Data processing
Scikit-learn: Machine learning models
Deep Learning: Movie embeddings and similarity scoring
Pickle: Model serialization
JavaScript (Frontend): Enhances interactivity

# Project Structure

Movie Recommender System/
│── app.py                   # Streamlit app for frontend  
│── main.py                   
│── dataset.csv               # Movie dataset  
│── movies_list.pkl           # Serialized movie data  
│── similarity.pkl            # Precomputed similarity matrix  
│── Movie_Recommender_System_Using_Machine_Learning.ipynb  # Notebook with ML approach  
│── frontend/                 # Frontend code  
│   ├── package.json          
│   ├── rollup.config.js      
│   ├── README.md             
└── requirements.txt          # Dependencies  

# Setup Instructions
1. Clone the Repository

git clone https://github.com/OmkarMagare27/movie-recommender-system.git
cd movie-recommender-system

2. Install Dependencies
Dataset link: https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k?fbclid=IwAR2MpWrWpcw2QNCv_FZg2l0sjBh9xAvhrqtnZBO9K-QS6PHI1aHkdB6qLa0

3. Run the Application

streamlit run app.py
The application will be accessible at http://localhost:8501/.

# How It Works
Data Processing: The dataset is preprocessed, and movie embeddings are generated.
Model Training: A deep learning model is trained to generate similarity scores.
Recommendation System: The backend fetches recommendations based on input.
User Interface: Users can search for movies and receive recommendations via Streamlit.

# Future Enhancements
Improve model accuracy with hybrid collaborative filtering.
Expand dataset with user ratings for better recommendations.
Enhance frontend with React or a more dynamic framework.

# Contribution
Feel free to open issues or submit pull requests for improvements.
