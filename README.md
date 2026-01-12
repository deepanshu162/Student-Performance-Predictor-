<h1>🎓 Student Performance Predictor</h1>

<p>
A <strong>Machine Learning–based project</strong> that predicts a student's
<strong>Performance Index</strong> using academic, lifestyle, and activity-related factors.
The project follows a <strong>complete ML pipeline</strong> — from data analysis to
model training, evaluation, and user prediction.
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
This project uses a <strong>Random Forest Regressor</strong> to predict student performance
based on:
</p>

<ul>
    <li>Hours studied</li>
    <li>Previous academic scores</li>
    <li>Sleep hours</li>
    <li>Extracurricular activities</li>
    <li>Practice of sample question papers</li>
</ul>

<p>
It is designed to be <strong>modular, reusable, and beginner-friendly</strong>, making it suitable for:
</p>

<ul>
    <li>Academic mini/major projects</li>
    <li>Resume & portfolio projects</li>
    <li>Learning end-to-end ML workflows</li>
</ul>

<hr>

<h2>🗂️ Project Structure</h2>

<pre>
Student-Performance-Predictor
│
├── StudentPerformance.csv
├── analyze_data.py
├── load_and_eda.py
├── preprocess.py
├── train_model.py
├── evaluate_model.py
├── predict.py
├── model.pkl
├── preprocessor.pkl
├── .tmp/
└── README.html
</pre>

<hr>

<h2>📊 Dataset</h2>

<p><strong>File:</strong> StudentPerformance.csv</p>

<p><strong>Target Variable:</strong></p>
<ul>
    <li>Performance Index</li>
</ul>

<p><strong>Input Features:</strong></p>
<ul>
    <li>Hours Studied</li>
    <li>Previous Scores</li>
    <li>Extracurricular Activities (Yes/No)</li>
    <li>Sleep Hours</li>
    <li>Sample Question Papers Practiced</li>
</ul>

<hr>

<h2>⚙️ Technologies Used</h2>

<ul>
    <li>Python</li>
    <li>Pandas & NumPy</li>
    <li>Scikit-learn</li>
    <li>Joblib</li>
    <li>Random Forest Regressor</li>
</ul>

<hr>

<h2>🔍 Workflow Pipeline</h2>

<ol>
    <li>Data Analysis</li>
    <li>Exploratory Data Analysis (EDA)</li>
    <li>Data Preprocessing</li>
    <li>Model Training</li>
    <li>Model Evaluation</li>
    <li>User Input-Based Prediction</li>
</ol>

<hr>

<h2>🚀 How to Run the Project</h2>

<h3>1️⃣ Install Dependencies</h3>
<pre>
pip install pandas numpy scikit-learn joblib
</pre>

<h3>2️⃣ Run Data Analysis</h3>
<pre>
python analyze_data.py
python load_and_eda.py
</pre>

<h3>3️⃣ Preprocess the Data</h3>
<pre>
python preprocess.py
</pre>

<h3>4️⃣ Train the Model</h3>
<pre>
python train_model.py
</pre>

<h3>5️⃣ Evaluate the Model</h3>
<pre>
python evaluate_model.py
</pre>

<h3>6️⃣ Make Predictions</h3>
<pre>
python predict.py
</pre>

<p>Or using command-line arguments:</p>

<pre>
python predict.py --hours_studied 6 --previous_scores 78 --extracurricular_activities Yes --sleep_hours 7 --sample_papers_practiced 4
</pre>

<hr>

<h2>📈 Model Performance</h2>

<ul>
    <li>R² Score: ~0.99 (Test Data)</li>
    <li>Low MAE & RMSE</li>
    <li>Overfitting check included</li>
    <li>Feature importance for explainability</li>
</ul>

<hr>

<h2>🧠 Key Features</h2>

<ul>
    <li>End-to-end ML pipeline</li>
    <li>Modular Python scripts</li>
    <li>Saved models & preprocessors</li>
    <li>Explainable predictions</li>
    <li>Resume-ready project</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<strong>Deepanshu Gupta</strong><br>
Data Science & Machine Learning Enthusiast
</p>

<hr>

<p>
⭐ If you like this project, consider starring the repository on GitHub!
</p>

