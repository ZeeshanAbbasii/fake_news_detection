# Fake News Detection

A machine learning system to detect fake news using LSTM and Naïve Bayes classifiers, built with Python and PyTorch.

## Project Structure

fake_news_detection/
├── data/
│   ├── archive/            # Fake.csv, True.csv (not tracked)
│   └── processed/          # cleaned_data.csv, news_combined.csv, vocab.pkl (not tracked)
├── models/                 # model.pth (not tracked)
├── notebooks/
│   └── cleaned_notebook.ipynb  # Main notebook
├── requirements.txt        # Dependencies
├── .gitignore              # Ignored files
├── README.md               # This file
└── LICENSE                 # License


## Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/ZeeshanAbbasii/fake_news_detection.git
   cd fake_news_detection

Install dependencies:

pip install -r requirements.txt

Usage
Run cleaned_notebook.ipynb to preprocess data, train LSTM/Naïve Bayes models, and evaluate (Naïve Bayes achieves 92.86% accuracy).

Results
Naïve Bayes: 92.86% accuracy, F1 score 0.9286.
LSTM: See notebook for validation metrics.
License
MIT License (see LICENSE file).