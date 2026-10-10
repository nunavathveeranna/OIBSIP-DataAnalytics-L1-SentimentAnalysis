# Sentiment Analysis Using Machine Learning

## Project Overview
This project uses Natural Language Processing (NLP) and machine learning to classify customer reviews into three sentiment categories: positive, negative, and neutral. The goal is to understand customer opinions and evaluate different classification algorithms.

## Objectives
- Analyze sentiment class distribution.
- Clean and preprocess textual reviews.
- Convert text into numerical features using TF-IDF.
- Train and compare multiple machine learning classifiers.
- Evaluate model performance and analyze misclassified reviews.
- Visualize sentiment distribution and frequently occurring words.

## Dataset
- **Source:** [Flipkart Product Customer Reviews Dataset – Kaggle](https://www.kaggle.com/datasets/niraliivaghani/flipkart-product-customer-reviews-dataset)
- **Loading:** KaggleHub
- **Input:** Customer review text.
- **Target:** Sentiment label (positive, negative, or neutral).

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- NLTK concepts and text preprocessing
- Matplotlib and Seaborn
- WordCloud
- KaggleHub

## Machine Learning Models
1. **Multinomial Naive Bayes:** A probabilistic classifier suitable for text classification using TF-IDF features.
2. **Logistic Regression:** A classification algorithm that learns decision boundaries to predict sentiment categories.

## Methodology
1. Load the dataset directly from Kaggle.
2. Inspect the dataset and analyze sentiment class distribution.
3. Clean text by converting it to lowercase and removing URLs, punctuation, numbers, and stopwords.
4. Convert reviews into numerical vectors using TF-IDF.
5. Split the dataset into training and testing sets using an 80:20 ratio.
6. Train both classification models.
7. Evaluate performance using accuracy, precision, recall, F1-score, classification reports, and confusion matrices.
8. Visualize sentiment distribution and generate word clouds for each sentiment class.
9. Examine five misclassified examples per model and discuss possible reasons for errors.
10. Compare both models and select the best one based on macro F1-score.

## Evaluation Metrics
- Accuracy
- Macro Precision
- Macro Recall
- Macro F1-score
- Weighted F1-score
- Confusion Matrix

## Expected Outcome
The project demonstrates how NLP and machine learning can automatically categorize customer reviews by sentiment. Comparing multiple models helps identify a suitable approach for analyzing customer feedback.

## Applications
- Customer feedback analysis
- Product review classification
- Customer satisfaction monitoring
- Identification of common complaints
- Public opinion analysis

## How to Run
1. Open Google Colab or Jupyter Notebook.
2. Install the required libraries:

   `pip install "kagglehub[pandas-datasets]" wordcloud`

3. Run the notebook cells in sequence.
4. Review the evaluation metrics, visualizations, misclassified examples, and sample prediction.

## Conclusion
This project demonstrates an end-to-end sentiment analysis workflow, from text preprocessing and TF-IDF feature extraction to model evaluation and error analysis. The best-performing model is selected using macro F1-score, which gives equal importance to each sentiment class.