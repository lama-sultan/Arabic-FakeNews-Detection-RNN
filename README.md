
# Arabic Fake News Detection using RNN

## Overview
This project focuses on detecting fake news written in Arabic using a Recurrent Neural Network (RNN). With the rapid spread of misinformation, especially in the Arab world, this model aims to contribute to the limited research available for Arabic-language fake news detection. The goal is to build an effective system that can classify news articles as real or fake based on their textual content.

## Features
- Arabic text preprocessing (normalization, stopword removal, etc.)
- Tokenization and sequence padding using Keras
- RNN-based model architecture (with LSTM or GRU)
- Accuracy evaluation, confusion matrix, and classification report

## Dataset
The dataset used in this project was **custom-built** by scraping Arabic news articles from various trusted and untrusted websites. Each article was manually labeled as either **real** or **fake** based on the credibility of the source and the content. This approach ensures a more relevant and realistic dataset for Arabic fake news detection.

> **Note:** The dataset is not publicly available due to source restrictions, but it can be shared upon request for academic and research purposes.

## Requirements
To run this project, you'll need the following Python libraries:
- Python 3.x
- TensorFlow / Keras
- NumPy
- pandas
- scikit-learn
- nltk
- matplotlib

Install them using:
```bash
pip install -r requirements.txt
How to Run
1.	Open the Jupyter Notebook Arabic-Fake-News-RNN-MainCode.ipynb.
2.	Run the notebook cell by cell:
o	Data loading and preprocessing
o	Tokenization and embedding
o	Model building and training
o	Evaluation and results
3.	You can experiment with different parameters (e.g., epochs, embedding size, model type).
Results
The RNN model showed promising results in detecting fake news in Arabic texts. It successfully captures sequential patterns in the language, demonstrating the effectiveness of deep learning methods in Arabic NLP tasks.
License
This project is intended for educational and research purposes only. Commercial use or redistribution of the dataset or code is not permitted without prior approval.
Contributors
Lama Alzu’bi – Model development, data collection, and implementation

