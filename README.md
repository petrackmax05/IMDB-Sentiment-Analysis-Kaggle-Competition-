# IMDB-Sentiment-Analysis-Kaggle-Competition-
Sentiment analysis project using NLP techniques to classify IMDB movie reviews as positive or negative, leveraging TF-IDF feature extraction and machine learning models.

# IMDB Sentiment Analysis (Kaggle Project)

## Description
This project performs sentiment analysis on movie reviews using Natural Language Processing (NLP) techniques. The goal is to classify reviews as positive or negative based on their text content.

The project includes data cleaning, feature extraction using TF-IDF, and model building using Logistic Regression and Random Forest classifiers.

---

## Tools & Technologies
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- BeautifulSoup (for text cleaning)

---

## Dataset
The dataset comes from the Kaggle IMDB Sentiment Analysis competition and includes:
- `labeledTrainData.tsv` (training data with sentiment labels)
- `testData.tsv` (unlabeled test data)

Each review is labeled:
- `1` = Positive  
- `0` = Negative  

---

## How to Run the Project

1. Install required libraries:

2. Place the dataset files in the project directory:
- `labeledTrainData.tsv`
- `testData.tsv`

3. Run the script:


---

## Project Features

- Text cleaning using BeautifulSoup and regular expressions
- Conversion of text into numerical features using TF-IDF
- Train/test split for model validation
- Logistic Regression model for sentiment classification
- Random Forest model comparison
- Visualizations including:
  - Sentiment distribution
  - Confusion matrix
  - Top word frequency analysis

---

## Results

- Logistic Regression achieved ~88% accuracy
- Random Forest achieved ~83% accuracy
- Logistic Regression performed better for this dataset
- TF-IDF proved effective for feature extraction

---

## Output

- Generates a `submission.csv` file containing predictions for test data
- File can be uploaded to Kaggle for competition scoring


---

## Author
Max Petrack  
University of Mount Union  
Data Science & Analytics (Minor: Computer & Network Security)
