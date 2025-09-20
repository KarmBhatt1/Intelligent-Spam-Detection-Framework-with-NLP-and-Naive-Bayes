This repository presents an advanced spam detection system leveraging state-of-the-art Natural Language Processing (NLP) techniques combined with classical probabilistic classifiers. The framework is meticulously designed to preprocess raw textual data, extract salient features, and classify messages with high precision. Both SMS and email datasets are considered, allowing the system to handle diverse textual inputs effectively.
Key components include:

Comprehensive Data Cleaning: Removal of duplicates, handling of missing values, and renaming for semantic clarity.

Exploratory Data Analysis (EDA): Distribution analysis, correlation heatmaps, and visualization of textual properties (number of words, characters, sentences).

Text Preprocessing Pipeline:

Lowercasing and tokenization

Stopword removal and punctuation handling

Stemming using Porter Stemmer

Feature Engineering:

Count of characters, words, and sentences

TF-IDF vectorization for transforming text into numerical feature space

Modeling:

Gaussian Naive Bayes (GNB)

Multinomial Naive Bayes (MNB)

Bernoulli Naive Bayes (BNB)

Evaluation Metrics:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

Visualization:

Word clouds for spam and ham corpora

Histograms for word, character, and sentence distributions

Heatmaps for correlation and model performance

Dataset

The dataset used (spam.csv) contains SMS/email messages labeled as ham (legitimate) or spam. It includes over 5,000 messages, providing a diverse and realistic corpus for model training and evaluation.

Columns:

v1: Original label (ham/spam) → mapped to output (0/1)

v2: SMS/Email text → renamed to sms/email

Unnamed: 2,3,4: Dropped as redundant
