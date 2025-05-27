# 📄 Document Classifier: Text Mining Project

This repository contains a complete pipeline for classifying Reddit posts into two categories: **Data Science** and **Game of Thrones**.  
It encompasses data preprocessing, model training, evaluation, and deployment-ready prediction scripts.

## 📁 Project Structure

```
document-classifier-textmining/
├── data/
│   ├── reddit_posts.csv
│   ├── GameofThrones.csv
│   ├── reddit_database.csv
│   ├── best_model.pkl
│   ├── tfidf_vectorizer.pkl
│   └── label_encoder.pkl
├── src/
│   └── doc_classifier_tm.ipynb
├── README.md
└── LICENSE
```

## 🧠 Features

- **Data Preprocessing**: Cleaning, emoji removal, and text normalization.
- **Model Training**: Utilizes multiple algorithms including Naive Bayes, Logistic Regression, and SVM.
- **Evaluation**: Calculates accuracy, precision, recall, and F1-score to select the best model.
- **Model Persistence**: Saves the trained model, TF-IDF vectorizer, and label encoder for future use.
- **Prediction Script**: Loads saved components to predict categories for new text inputs.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Install required packages:

```bash
pip install -r requirements.txt
```

### Training the Model

Navigate to the `src/` directory and run the .ipynb file

This script will:

- Load and preprocess data from `data/reddit_posts.csv`.
- Train multiple models and evaluate their performance.
- Save the best-performing model and associated components in the `data/` directory.
- let you make predictions (single & batch, both. )

## 📝 Dataset Details

- **reddit_posts.csv**: Combined and cleaned dataset containing Reddit posts related to Data Science and Game of Thrones.
- **GameofThrones.csv**: Raw dataset with Game of Thrones-related Reddit posts.
- **reddit_database.csv**: Raw dataset with Data Science-related Reddit posts.

## 📦 Saved Components

- **best_model.pkl**: Serialized best-performing model.
- **tfidf_vectorizer.pkl**: Serialized TF-IDF vectorizer used for feature extraction.
- **label_encoder.pkl**: Serialized label encoder mapping categories to numerical labels.

## 📄 License

This project is licensed under the [GPL-3.0 License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## 📬 Contact

For any inquiries or feedback, please open an issue in the repository.

