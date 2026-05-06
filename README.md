# Placement-Reader
Overview

The AI-Based Placement Readiness Prediction System is a machine learning-powered web application designed to evaluate a student's readiness for campus placements. The system predicts a readiness score using academic performance, technical skills, communication ability, internship experience, and project work.

The project uses a Gradient Boosting Regressor trained on structured student data and provides real-time predictions directly in the browser without requiring any backend server.

🚀 Features
Predicts placement readiness score
Interactive and modern web interface
Real-time prediction in browser
Skill analysis dashboard
Feature importance visualization
No backend required
Lightweight deployment using GitHub Pages
🧠 Machine Learning Model
Algorithm: Gradient Boosting Regressor
Learning Rate: 0.05
Estimators: 200 Trees
Scaler Used: MinMaxScaler
Evaluation Metric: R² Score

The model was trained in Python using Scikit-learn and later converted into JavaScript-compatible JSON format for frontend deployment.

📊 Features Used
Feature	Description
CGPA	Academic performance
DSA Score	Coding and problem-solving ability
Communication Skills	Soft skill evaluation
Internship Experience	Practical industry exposure
Projects	Number of completed projects
🛠️ Technologies Used
Frontend
HTML
CSS
JavaScript
Machine Learning
Python
Scikit-learn
Pandas
NumPy
Google Colab
⚙️ Workflow
User Input → Feature Scaling → ML Model → Readiness Prediction → Dashboard Output
📈 Model Performance
High prediction accuracy
R² Score ≈ 0.9
Fast real-time inference
🌐 Deployment

The project can be deployed easily using:

GitHub Pages
Netlify
Vercel
