##  Movie Recommender System

A simple and intuitive movie recommendation web app built with Streamlit, leveraging content-based filtering using movie metadata and cosine similarity. Users can select a movie and get the top 5 similar movie recommendations.

# Features
🎥 Select any movie from a dropdown list of popular titles.
🎯 Get top 5 content-based movie recommendations.
✨ Clean, responsive UI with custom CSS styling.

# Tech Stack
Python 3.7+
Streamlit for the web interface
Pandas for data handling
Scikit-learn (cosine similarity) for recommendation logic
Pickle for storing precomputed data

Project Structure

Movie-Recommender/
├── movie_dict.pkl         # Pickled dictionary of movie metadata
├── similarity.pkl         # Pickled similarity matrix
├── app.py                 # Main Streamlit application
├── assets/                # (Optional) images, CSS, GIFs
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation


# Getting Started

# Prerequisites
 - Python 3.7 or higher
 - Git

# Installation
1.Clone the repository
git clone https://github.com/<your-username>/Movie-Recommender.git
cd Movie-Recommender

2.Create and activate a virtual environment
python -m venv venv
source venv/bin/activate    # On macOS/Linux
venv\\Scripts\\activate   # On Windows

3.Install dependencies
pip install -r requirements.txt

4.Download or place data files
Ensure movie_dict.pkl and similarity.pkl are in the project root.

5.Run the app
streamlit run app.py
The app will open in your default browser at http://localhost:8501.

# Usage
Choose a movie from the dropdown menu.
Click Show Recommendation.
View the top 5 recommended movies displayed with styled cards.

# Contributing
Contributions are welcome! Feel free to open issues or submit pull requests:
1. Fork the repository
2. Create a feature branch (git checkout -b feature/...)
3. Commit your changes (git commit -m "Add ...")
4. Push to the branch (git push origin feature/...)
5. Open a Pull Request

# Future Improvements
🎞️ Include movie posters with each recommendation
🌐 Deploy the app on Heroku or Streamlit Cloud
🔍 Implement collaborative filtering for improved accuracy
⚡ Optimize performance for large datasets


# Contact

Developed by Deep
GitHub: @deepkakadiya7
LinkedIn: Deep Kakadiya

