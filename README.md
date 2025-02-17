# Student-Performance-Indicator-Prediction-
# Student Performance Indicator (Prediction)

## 📌 Overview
This project predicts students' math subject marks based on various categorical and numerical features. It follows an **End-to-End Machine Learning Project Lifecycle**, covering data ingestion, transformation, model training, evaluation, and deployment. This approach mirrors real-world **industry-level ML projects**.

## 🛠 Tech Stack
- **Programming Language:** Python
- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Logging & Exception Handling:** Logging module
- **Deployment:** Flask (Upcoming), Cloud Platforms (Upcoming)
- **Version Control:** Git & GitHub

---

## 📂 Project Structure
```
student_performance_prediction/
│── notebooks/                  # Jupyter notebooks for EDA and model training
│── src/
│   ├── components/              # Core ML components (Data Ingestion, Transformation, Training, etc.)
│   ├── pipeline/                # Training and Prediction Pipelines
│   ├── utils/                   # Utility functions
│   ├── exception.py             # Custom exception handling
│   ├── logger.py                # Logging setup
│── static/                      # Static files (for future Flask app UI)
│── templates/                   # HTML templates (for future Flask app UI)
│── app.py                       # Flask API for model prediction (Upcoming)
│── requirements.txt             # Dependencies
│── README.md                    # Project documentation
│── setup.py                      # Package setup
│── config.yaml                   # Configurations
│── .gitignore                    # Ignore unnecessary files
```

---

## 🚀 Project Workflow

1️⃣ **GitHub and Code Setup**
   - Repository setup, version control, and project organization.

2️⃣ **Project Structure, Logging & Exception Handling**
   - Industry-level coding standards, logging, and error handling mechanisms.

3️⃣ **Problem Statement, EDA, and Model Training**
   - Exploratory Data Analysis (EDA), feature selection, and preprocessing.

4️⃣ **Data Ingestion Implementation**
   - Extract, Transform, Load (ETL) pipeline to fetch and prepare data.

5️⃣ **Data Transformation Implementation Using Pipelines**
   - Data cleaning, feature engineering, and transformations.

6️⃣ **Model Training and Model Evaluation Component**
   - Model selection, training, evaluation metrics.

7️⃣ **Model Hyperparameter Tuning**
   - GridSearchCV, RandomizedSearchCV for optimizing model performance.

8️⃣ **Prediction Pipeline Using Flask Web App** (Upcoming)
   - Building a REST API to serve predictions.

9️⃣ **Project Deployment** (Upcoming)
   - Hosting model on cloud platforms with CI/CD pipeline.

---

## 🔧 Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/Pabbidi/Student-Performance-Indicator-Prediction.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Student-Performance-Indicator-Prediction
   ```
3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate     # For Windows
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
5. Run the application (Flask API - upcoming feature):
   ```sh
   python app.py
   ```

---

## 📢 Future Enhancements
✅ Web Application using Flask (Interactive UI)  
✅ Deployment on Cloud Platforms  
✅ Integration with CI/CD pipelines  
✅ More advanced feature engineering techniques  

---


