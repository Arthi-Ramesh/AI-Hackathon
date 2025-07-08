# AI-Hackathon
Categorizing Social Media Posts for Mental Health Awareness and Early Intervention Using Machine Learning.

## Project Purpose

The purpose of this research is to **categorize social media posts** into **predefined mental health conditions** using content-based machine learning classification.

By leveraging feature engineering, dataset balancing, and model evaluation techniques, our goal is to:
- Accurately **predict users’ emotions and behavioral signals**
- Promote **early intervention**
- Increase **awareness around mental health** using computational methods

---

##  Delving into Our Dataset

Our dataset contains rich, annotated narratives of mental health challenges and emotional states, helping us build effective classifiers:

- **Diverse Narratives**: Real-world stories expressing depression, anxiety, PTSD, and personal coping strategies.
- **Detailed Annotations**: Labeled symptoms and behaviors that support multi-class classification.
- **Risk Factor Identification**: Recognizing emotional triggers and stress-inducing life events.
- **Contextual Impact**: Data includes unique perspectives (e.g., military service), emphasizing the mental toll of certain life circumstances.

---

## Project Pipeline

### 1️⃣ Data Loading & Duplication
- Loads a JSON file with annotated primate-related mental health posts.
- Duplicates data to expand the dataset for better model generalization.

### 2️⃣ Balancing the Dataset
- Increases the dataset to **2000 balanced samples** by duplicating underrepresented entries.

### 3️⃣ Data Preprocessing
- Flattens nested annotation structures.
- Splits the dataset into **80% training** and **20% testing**.
- Text data is transformed into numerical features using **TF-IDF vectorization**.

### 4️⃣ Model Training
- A **Decision Tree Classifier** is used for training.
- The model learns classification patterns from the training data.

### 5️⃣ Model Evaluation
- Model performance is evaluated using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1 Score**
- Plots **ROC curves** for each class.

### 6️⃣ Visualization
- A variety of visualizations are included:
  - **Pie chart** and **bar chart** of prediction distribution
  - **Scatter plot with jitter** to explore prediction clusters

---

## ⚙ Key Technologies

- Python
- scikit-learn
- pandas
- matplotlib / seaborn
- TF-IDF Vectorizer
- Decision Tree Classifier

---
