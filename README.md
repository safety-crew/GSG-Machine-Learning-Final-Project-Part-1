# Part 1: Supervised Learning - Classifying Text or Images
### Data Analysis:

- I have a balanced dataset with 120,000 training samples and 7,600 test samples
- Each category (World, Sports, Business, Science/Technology) has equal representation
- The visualization dashboard shows the distribution and sample headlines


### Text Preprocessing:

- Implemented comprehensive text preprocessing including:

  - Lowercasing to normalize text
  - Special character removal
  - Tokenization using NLTK
  - Stopword removal to eliminate common words
  - Lemmatization to reduce words to their base form




### TF-IDF Vectorization:

- Used TfidfVectorizer with optimized parameters:

  - max_features=5000 to control dimensionality
  - min_df=5 to remove rare terms
  - max_df=0.95 to remove extremely common terms
  - ngram_range=(1, 2) to capture phrases




### Model Training:

- Implemented four different classifiers:

  - Logistic Regression: Good for text classification with large feature spaces
  - Decision Tree: Provides interpretable rules
  - Gradient Boosting: Powerful ensemble method
  - KNN: Useful for comparison with different approach




### Evaluation:

- Comprehensive evaluation using:

  - Accuracy scores
  - Precision, recall, and F1-score for each category
  - Visualization of model comparisons
  - Feature importance analysis for interpretability
