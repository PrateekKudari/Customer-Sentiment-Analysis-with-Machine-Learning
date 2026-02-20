# Customer-Sentiment-Analysis-with-Machine-Learning
A machine learning project that automatically classifies customer reviews as positive, negative, or neutral with 91% accuracy.
 Project Overview
This project analyzes 23,000+ customer reviews from an e-commerce clothing store using natural language processing and machine learning.
Key Results:

91% classification accuracy
Compared 4 different ML models
Created interactive Power BI dashboard
Reduced manual analysis time by 95%

 Tech Stack

Python - Data processing and ML
Scikit-learn - Machine learning models
NLTK - Natural language processing
Pandas & NumPy - Data manipulation
SQL - Data storage and queries
Power BI - Data visualization

 Dataset

Source: Women's E-Commerce Clothing Reviews (Kaggle)
Size: 23,486 reviews
Features: Review text, rating, age, department, product details

 Quick Start
1. Clone the repository
bashgit clone https://github.com/yourusername/sentiment-analysis-ml-project.git
cd sentiment-analysis-ml-project
2. Install dependencies
bashpip install -r requirements.txt
3. Download NLTK data
pythonimport nltk
nltk.download('stopwords')
nltk.download('wordnet')
4. Download dataset

Get data from Kaggle
Place CSV file in data/raw/ folder

5. Run the pipeline
bash# Phase 1: Data preprocessing
python src/phase1_data_setup.py

# Phase 2: Train ML models
python src/phase2_sentiment_model.py
 Results
ModelAccuracyLogistic Regression91.2% Naive Bayes86.4%VADER78.3%TextBlob72.1%
Business Insights:

82.5% of reviews are positive
Average rating: 4.2/5
Top complaint: Sizing issues
Most praised feature: Comfort

 Project Structure
├── data/                   # Data files
├── src/                    # Python scripts
├── models/                 # Trained models
├── visualizations/         # Charts and Power BI files
├── docs/                   # Documentation
└── requirements.txt        # Dependencies

 What I Learned
Text preprocessing and cleaning
TF-IDF vectorization
Training and evaluating ML models
Handling imbalanced datasets
Creating business dashboards

 Future Improvements

 Deploy as REST API
 Try deep learning models (BERT)
 Add real-time predictions
 Multi-language support

Author
Prateek Kudari
