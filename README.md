# AI-ML_Internship_tasks_01
**Task_1:** News topic classifier using BERT
Here is the project link:**https://drive.google.com/file/d/1Ate0dThxX7-iKKOSbbIZ_3h9tcN1wj49/view?usp=drivesdk**
📌 Project Overview
This project builds a news classification system using BERT (Bidirectional Encoder Representations from Transformers) to automatically categorize news articles into predefined topics such as politics, sports, technology, business, etc.
The model leverages deep learning and natural language processing techniques to understand the context of news text and provide accurate predictions.
🎯 Objectives
Classify news articles into different categories
Use pre-trained transformer models for better accuracy
Fine-tune BERT for text classification
Evaluate model performance using standard metrics
🧠 Technologies Used
Python
PyTorch / TensorFlow
Transformers (Hugging Face)
Pandas, NumPy
Scikit-learn
Matplotlib / Seaborn
📂 Dataset
The dataset contains:
News headlines or full articles
Corresponding category labels (e.g., Sports, Politics, Tech, Business)


**Task_2:** End to end ML pipeline with scikit learn pipeline API for predicting customer churn
📌 Project Overview
Customer churn prediction is a machine learning project that aims to identify customers who are likely to leave (churn) a company. By predicting churn, businesses can take proactive steps to retain customers and improve overall revenue.
🎯 Objectives
Predict whether a customer will churn or not
Analyze factors influencing customer churn
Build and evaluate machine learning models
Improve customer retention strategies
🧠 Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
Jupyter Notebook
📂 Dataset
The dataset contains customer information such as:
Gender
Age
Tenure
Monthly Charges
Contract Type
Payment Method
Churn (Target Variable)
⚙️ Project Workflow
1️⃣ Data Preprocessing
Handling missing values
Encoding categorical variables
Feature scaling
2️⃣ Exploratory Data Analysis (EDA)
Data visualization
Correlation analysis
Identifying key churn factors
3️⃣ Model Building
Logistic Regression
Decision Tree
Random Forest
4️⃣ Model Evaluation
Accuracy Score
Confusion Matrix
Precision, Recall, F1-score
📊 Results
Compared multiple algorithms
Selected best-performing model based on accuracy and evaluation metrics
Identified key features affecting churn


**Task_3:** Context aware chatbot using langchain or RAG
# 🤖 RAG Chatbot — Complete Setup Guide
Here is the the project link:**https://drive.google.com/file/d/1OihtGgCqt18COaUGxULfkJ7y0J2KLSEP/view?usp=drivesdk**
## What This Project Does

A conversational chatbot that:
- **Reads** your custom text documents (knowledge base)
- **Embeds** them into a FAISS vector store using grok embeddings
- **Retrieves** relevant chunks when you ask a question (RAG)
- **Generates** a context-aware answer using grok
- **Remembers** the last 6 turns of conversation (sliding window memory)
- **Shows** which source documents were used for each answer

---

## 📁 Project Structure

```
rag_chatbot/
├── app.py               ← Main Streamlit application
├── requirements.txt     ← Python dependencies
├── .env.example         ← API key template
├── .env                 ← Your actual API key (create this yourself)
└── data/                ← Your knowledge base (put .txt files here)
    ├── artificial_intelligence.txt
    ├── python_programming.txt
    └── data_science.txt
```
