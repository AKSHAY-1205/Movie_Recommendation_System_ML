🎬 Movie Recommendation System 🍿

This is a Flask-based web application that provides movie recommendations based on similarity scores. The system takes a movie name as input and suggests similar movies using preprocessed data.

🚀 Features

🔍 Enter a movie name to get recommendations

🤖 Uses a similarity matrix for recommendations

🎞️ Displays top 10 similar movies

🖥️ User-friendly interface with error handling

🛠 Tech Stack

🖥 Backend: Flask (Python)

🎨 Frontend: HTML, CSS (Jinja2 templating)

📊 Data Handling: Pandas, Pickle

📥 Installation

1️⃣ Clone the Repository

2️⃣ Install Dependencies

Make sure you have Python installed, then run:

3️⃣ Generate the Similarity Matrix 🛠️

Before running the app, you need to generate similarity.pkl by executing:

This ensures that the required similarity matrix is available.

4️⃣ Run the Application 🎬

Open your browser and go to http://127.0.0.1:5000/ to access the app.

🌍 Deployment

This project is deployed on Render (or any hosting service you used). You can access it here:
🎥 Live Demo

📂 File Structure 📁

⚠️ Notes ⚠️

Ensure that movies.csv is present before running generate_recommendations.py.

If similarity.pkl is missing, rerun generate_recommendations.py before starting app.py.

If you face errors related to missing files, manually upload them to your hosting service.

👥 Contributors

🙋‍♂️ Your Name - Developer

📜 License 📄

This project is open-source and available under the MIT License.

