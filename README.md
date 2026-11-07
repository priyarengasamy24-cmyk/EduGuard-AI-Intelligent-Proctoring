 🛡️ EduGuard AI – Intelligent Proctoring System

 AI-Powered Online Exam Monitoring Using Machine Learning

📌 Overview

EduGuard AI is an intelligent online examination proctoring system designed to identify suspicious student behaviour during online exams using Machine Learning.

Traditional online proctoring systems may incorrectly flag innocent students due to normal movements, background noise, or temporary distractions. EduGuard AI addresses this challenge by analyzing multiple behavioural signals and applying a strict prediction threshold to reduce false accusations.

 🎯 Objectives

- Detect suspicious examination activities.
- Analyze eye gaze and audio signals.
- Monitor tab-switch activities.
- Handle missing and asynchronous data.
- Reduce false positive cheating predictions.
- Improve fairness and reliability in online examinations.

   Key Features

- **Data Integration:** Combines video telemetry and system event logs.
- **Temporal Alignment:** Uses Pandas `merge_asof()` to align asynchronous timestamps.
- **Missing Data Handling:** Uses forward filling and interpolation.
- **Feature Engineering:** Creates 10-second rolling averages for sensor signals.
- **Machine Learning:** Implements a Random Forest Classifier with balanced class weights.
- **Ethical AI:** Applies a strict 90% prediction threshold to minimize false accusations.
- **Data Visualization:** Generates class distribution, sensor trends, correlation heatmaps, feature importance, and ROC curves.

Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning
- Random Forest Classifier

 Project Workflow

1. Data Ingestion
2. Temporal Data Alignment
3. Missing Data Processing
4. Feature Engineering
5. Exploratory Data Analysis
6. Random Forest Model Training
7. Ethical AI Threshold Optimization
8. Model Evaluation and Visualization

 Model Evaluation

The project compares two prediction thresholds:

| Evaluation | Default Threshold | Strict Threshold |
|---|---:|---:|
| Prediction Threshold | 50% | 90% |
| False Positives | 26 | 0 |
| Recall | 67% | 54% |

The strict threshold reduces false accusations, prioritizing student fairness over detecting every suspicious activity.

 Project Structure

EduGuard-AI-Intelligent-Proctoring/
│
├── AI_Student_code_FINAL.ipynb
├── README.md
├── requirements.txt
└── .gitignore


 How to Run

1. Clone this repository:

```bash
git clone https://github.com/USERNAME/EduGuard-AI-Intelligent-Proctoring.git
```

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook using Google Colab or Jupyter Notebook.

4. Run all cells sequentially to execute the complete Machine Learning workflow.

 Future Enhancements

- Real-time webcam-based monitoring.
- Deep Learning-based facial and behaviour analysis.
- Live suspicious activity alerts.
- Student and administrator dashboards.
- Integration with online examination platforms.

 Project Information

**Project:** EduGuard AI – Intelligent Proctoring AI  
**Domain:** Artificial Intelligence & Machine Learning  
**Intern:** Mohana Priya R

 License

This project is available under the MIT License.
