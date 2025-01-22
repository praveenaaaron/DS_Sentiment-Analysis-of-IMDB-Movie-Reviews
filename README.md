# Sentiment Analysis of IMDB Movie Reviews Using LSTM

## Problem Statement
Develop and evaluate an LSTM-based model to perform sentiment analysis on the IMDB Movie Reviews dataset, predicting whether a review is positive or negative.

## Skills Gained
- Textual data preprocessing
- Deep learning models for Natural Language Processing (NLP)

## Domain
Natural Language Processing (NLP)

- Python 3.8 or higher
- TensorFlow 2.x
- Matplotlib
- NumPy
## Approach
### 1. Dataset Loading
- Load the dataset using TensorFlow's built-in IMDB dataset.
- Inspect the dataset structure (integer-encoded words and labels).

### 2. Data Exploration
- Visualize the distribution of review lengths and label counts.
- Understand the vocabulary size and encoding.

### 3. Text Preprocessing
- Pad sequences to ensure uniform input size.
- Optionally, decode a few reviews back to text for better understanding.

### 4. Build the LSTM Model
- Use an embedding layer to convert integer-encoded words to dense vector representations.
- Add LSTM layers to capture sequential information.

### 5. Train the Model
- Compile the model with an appropriate loss function (binary_crossentropy for binary classification).
- Train using the training dataset and validate on the test set.

### 6. Evaluate the Model
- Calculate accuracy, precision, recall, and F1 score.
- Plot learning curves for loss and accuracy.

### 7. Make Predictions
- Test the model on custom reviews to validate performance.
- Decode predictions into "positive" or "negative" sentiments.

## Results
The model should achieve good accuracy, precision, recall, and F1 score with minimum loss.
