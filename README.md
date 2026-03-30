# AI-Based Sentiment Analysis & Consumer Behavior Pipeline

## 📌 Overview
This project presents a complete analytical pipeline for sentiment analysis and consumer behavior understanding using Amazon and Yelp datasets. It integrates classical machine learning, deep learning, and transformer-based models (RoBERTa-Large), along with interpretability techniques.

---

## 📂 Datasets
- **Amazon Reviews Dataset**
- **Yelp Reviews Dataset**

Both datasets are used for:
- Sentiment classification (Negative, Neutral, Positive)
- Cross-domain analysis
- Consumer behavior interpretation

---

## ⚙️ Pipeline

### 1. Data Preprocessing
- Lowercasing
- Removal of HTML tags, punctuation, and noise
- Tokenization & Lemmatization
- Stopword removal

---

### 2. Feature Engineering
- TF-IDF representation
- Sentence embeddings
- Text normalization

---

### 3. Models

#### Baselines
- SVM
- Naive Bayes
- Random Forest
- XGBoost

#### Deep Learning
- Bi-GRU

#### Proposed Model
- **RoBERTa-Large (Transformer-based LLM)**

---

### 4. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

### 5. Interpretability
- SHAP (feature importance)
- LIME (local explanations)
- Attention heatmaps
- SHAP–LIME agreement analysis
- Token stability analysis

---

### 6. Topic Modeling
- LDA (used for exploratory analysis)
- Topic interpretation for consumer behavior insights

---

### 7. Cross-Domain Analysis
- Amazon vs Yelp comparison
- Domain shift evaluation
- Token polarity strength differences
- Uncertainty analysis

---

## 📊 Key Insights
- Amazon reviews are more product-focused and structured
- Yelp reviews are more experiential and context-dependent
- Transformer models capture contextual sentiment effectively
- Interpretability reveals decision-making patterns in consumer behavior

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run preprocessing & EDA
3. Train baseline models
4. Train RoBERTa-large model
5. Generate interpretability plots

---

## 📌 Contribution
This work provides an **integrated analytical pipeline** combining:
- Deep learning
- Transformer models
- Explainability techniques
- Consumer behavior analysis

---

## 📄 License
This project is intended for academic and research purposes.
