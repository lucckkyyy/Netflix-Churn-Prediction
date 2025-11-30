🎬 Netflix-Style Churn Prediction
📘 Building a Machine Learning Case Study

I created this churn prediction project as a hands-on way to deepen my understanding of machine learning, data cleaning, and user behavior analytics.
Just like my portfolio website helped me grow in frontend development, this project helped me grow in feature engineering, ML modeling, and data storytelling.

This wasn’t just a model — it was a complete learning journey.

🧭 Project Motivation

I wanted to imagine how a company like Netflix analyzes user retention:

Why do users churn?

Which behaviors predict that a user may cancel?

What does engagement look like over time?

How can a simple model generate meaningful insights?

Using the IBM Telco Churn dataset, I transformed the telecom-style data into Netflix-style streaming behavior data, making the project feel realistic and industry-aligned.

🛠 Development Journey
Timeline & Approach

Duration: 1–2 days of focused ML exploration

Approach: Transform + engineer features to simulate Netflix user behavior

Focus: Clean datasets, interpretability, foundational ML modeling

🧠 Skills I Developed Through This Project
🔧 Data Cleaning & Wrangling

Handling missing values

Converting text values into numeric

Dropping unnecessary identifiers

Renaming columns for clarity (e.g., converting telecom terms → streaming terms)

🎛 Feature Engineering

One-hot encoding for categorical variables

Creating a synthetic engagement metric: WatchHours

Mapping Yes/No → binary labels

Generating Netflix-style features like:

MonthsSubscribed

MonthlySubscriptionFee

StreamingQuality

TotalAmountPaid

🤖 Machine Learning

Logistic Regression model

Train–test split

StandardScaler preprocessing

Model evaluation using:

Accuracy

Precision

Recall

F1-score

Confusion matrix

📊 Visualization

Confusion matrix heatmap

Dataset sample previews

Encoded feature inspection

📈 Technical Focus Areas
What I Worked On

Clean ML pipeline structure

Turning raw CSV data into analysis-ready format

Transforming telecom-style data into Netflix-style product analytics

Balancing interpretability with performance

Evaluating classification metrics the right way

Skills I Leveled Up

Feature engineering thinking

ML preprocessing (encoding + scaling)

Reading and interpreting ML evaluation metrics

Notebook structuring and storytelling

Project organization and documentation

📉 Model Performance

Accuracy: ~80%

Strong performance on non-churners

Good baseline performance for churn prediction

Confusion matrix and full classification report included

This is a realistic, industry-style starter model for streaming churn prediction.

🗂 Project Structure
Netflix Churn Prediction/
│── data/
│   └── telco_churn.csv
│── netflix_churn_analysis.ipynb
│── requirements.txt
│── README.md
└── venv/

🧪 How to Test This Project Yourself
1. Clone the repository
git clone https://github.com/lucckkyyy/Netflix-Churn-Prediction.git
cd Netflix-Churn-Prediction

2. Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate

3. Install the required packages
pip install -r requirements.txt

4. Launch the notebook
jupyter notebook


Open:

netflix_churn_analysis.ipynb


Run the cells to reproduce the churn prediction workflow.

🎯 The Learning Outcome

This project strengthened my ability to translate raw datasets into meaningful insights.
I learned to create Netflix-style features, build a clean ML pipeline, and document the project professionally.
It represents a significant step in my growth toward applied data science and user analytics.

Author: Aryan Rajguru
