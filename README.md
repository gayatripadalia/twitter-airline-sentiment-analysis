# Twitter Airline Sentiment Analysis
Classifying tweets about US airlines as positive, negative, or neutral using 
Natural Language Processing (NLP).
## About the Project
This project analyzes the **Kaggle US Airline Sentiment dataset** to predict 
the sentiment of tweets directed at major US airlines. It uses TF-IDF 
vectorization and Logistic Regression to build a text classification model.
## Tech Stack
Python | Pandas | NLTK | Scikit-learn | TF-IDF | Logistic Regression | Matplotlib | Seaborn
## Notebook Structure
| Cell | Description |
|------|-------------|
| Cell 1 | Import libraries and install dependencies |
| Cell 2 | Load and explore the dataset |
| Cell 3 | Visualize sentiment distribution |
| Cell 4 | Clean and preprocess tweet text |
| Cell 5 | Prepare data for ML (TF-IDF vectorization) |
| Cell 6 | Train the Logistic Regression model |
| Cell 7 | Evaluate model performance |
| Cell 8 | Plot confusion matrix |
| Cell 9 | Predict sentiment on custom tweets |
## Results
- Model accuracy: **85%+**
- See `confusion_matrix.png` and `sentiment_distribution.png` for visuals
## How to Run
1. Clone this repo
2. Open `sentiment.ipynb` in Jupyter Notebook or Google Colab
3. Upload `Tweets.csv` to the same folder
4. Run all cells in order
## Dataset
Kaggle US Airline Sentiment Dataset — contains ~14,000 tweets labeled 
as positive, negative, or neutral.
