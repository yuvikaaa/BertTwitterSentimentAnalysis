# Sentiment Analysis with BERT

This project performs sentiment analysis on Twitter data using a pre-trained BERT model. The dataset used is the **SMILE Twitter Emotion Dataset**, and the implementation is done in a Jupyter Notebook with PyTorch and HuggingFace's Transformers library.

## 📂 Project Structure

- `SentimentAnalysisBert.ipynb`: Jupyter notebook containing the full pipeline including EDA, preprocessing, model training, evaluation, and inference.

## 📊 Dataset

**SMILE Twitter Emotion Dataset**  
A dataset of tweets annotated with emotion categories.

- Loaded via `pandas` from a CSV file.
- Each entry contains:
  - `id`: Tweet identifier
  - `text`: Tweet content
  - `category`: Annotated emotion (e.g., happiness, sadness, etc.)

## 🚀 Features

- Exploratory Data Analysis (EDA) and preprocessing
- Tokenization using `BertTokenizer`
- Model architecture using `BertForSequenceClassification`
- Training and validation with PyTorch
- Evaluation metrics including accuracy
- Emotion classification on unseen data

## 🛠️ Libraries Used

- Python 3
- PyTorch
- Transformers (HuggingFace)
- Pandas
- NumPy
- tqdm