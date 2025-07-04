# 🎬 Movie Recommendation System 🍿

This is a Flask-based web application that provides movie recommendations based on similarity scores. The system takes a movie name as input and suggests similar movies using preprocessed data.

## 🚀 Features
- 🔍 Enter a movie name to get recommendations
- 🤖 Uses a similarity matrix for recommendations
- 🎞️ Displays top 10 similar movies
- 🖥️ User-friendly interface with error handling

## 🛠 Tech Stack
- **🖥 Backend:** Flask (Python)
- **🎨 Frontend:** HTML, CSS (Jinja2 templating)
- **📊 Data Handling:** Pandas, Pickle

## 📥 Installation
### 1️⃣ Clone the Repository
```sh
git clone [https://github.com/AKSHAY-1205/Movie_Recommendation_System_ML.git]
cd movie-recommendation-system
```
### 2️⃣ Install Dependencies
Make sure you have Python installed, then run:
```sh
pip install -r requirements.txt
```
### 3️⃣ Generate Similarity Matrix 🔄
Run the following script to generate `similarity.pkl` before starting the application:
```sh
python generate_recommendations.py
```
### 4️⃣ Run the Application ▶️
```sh
python app.py
```
Open your browser and go to `http://127.0.0.1:5000/` to access the app.

## 🌍 Deployment
This project is deployed on Render (or any hosting service you used). You can access it here:
[🎥 Live Demo](https://movie-recommendation-system-ml-1-66bo.onrender.com)

## 📂 File Structure 📁
```
📁 movie-recommendation-system/
├── 📜 app.py                # Main Flask application
├── 📜 generate_recommendations.py  # Script to create similarity.pkl
├── 📄 movies.csv            # Movie dataset
├── 🗂️ similarity.pkl        # Precomputed similarity matrix
├── 📁 templates/
│   ├── 📝 index.html        # Frontend template
├── 📁 static/
│   ├── 🎨 styles.css        # CSS for styling (if any)
├── 📜 requirements.txt      # Dependencies
├── 📖 README.md             # Project documentation
```

## ⚠️ Notes ⚠️
- Ensure that `movies.csv` is present before running the script.
- Run `generate_recommendations.py` first to create `similarity.pkl`.
- If you face errors related to missing files, upload them manually or ensure they are in the correct location.

## 👥 Contributors
- **🙋‍♂️ Your Name** - Developer

## 📜 License 📜
This project is open-source and available under the [MIT License](LICENSE).

