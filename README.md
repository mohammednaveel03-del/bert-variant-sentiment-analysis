## Opening the Notebook (Important)

GitHub may display this notebook as **"Invalid Notebook"** due to Colab-specific metadata.
This does NOT affect execution.

To open the notebook correctly:

1. Go to: https://colab.research.google.com
2. Click **GitHub**
3. Paste this repository URL:
   https://github.com/mohammednaveel03-del/bert-variant-sentiment-analysis
4. Select:
   `SentimentAnalysis_MohammedNaveel.ipynb`

The notebook will open and run normally in Google Colab.

# Accuracy–Latency Trade-off in Transformer-Based Sentiment Analysis

This repository contains a fully reproducible implementation of a comparative study evaluating BERT, RoBERTa, and DistilBERT for binary tweet sentiment classification.

The project analyzes the trade-off between predictive performance (Accuracy, F1-score) and inference efficiency (latency) under a unified experimental pipeline.

---

## Repository Contents

- SentimentAnalysis_MohammedNaveel.ipynb  
  Jupyter notebook containing the complete experimental pipeline.

- requirements.txt  
  List of Python libraries used in the notebook.

---

## Models Evaluated

- DistilBERT-base-uncased  
- BERT-base-uncased  
- RoBERTa-base  

---

## Dataset

A public Twitter sentiment dataset is loaded programmatically within the notebook.
After preprocessing and cleaning, 29,530 labeled tweets are used with stratified 80/10/10 train, validation, and test splits.

No external dataset files are required.

---

## How to Run

1. Open the notebook in **Google Colab**.
2. Run all cells from top to bottom.
3. All results (metrics and latency measurements) appear inside the notebook.

---

## Outputs

The notebook produces:
- Accuracy and F1-score on the test set
- Inference latency measurements
- Comparative analysis of model performance

---

## Notes

If GitHub shows an “Invalid Notebook” preview message, please open the notebook in Google Colab.  
The notebook runs correctly there.

---

## Author

Mohammed Naveel  
Bahçeşehir University (BAU)
