# Phishing Detection with BERT

Project Submission for CSI3033 - Web Mining & Social Network Analysis submitted by Dev Abhiram (20MIC0112) & Vishesh Choudhary (20MIC0097)

This project employs BERT, a powerful language model, for phishing website detection. It trains on a dataset of URL features and labels, distinguishing between legitimate and phishing URLs.

## How It Works
- **Dataset**: Utilizes a dataset (`phishing.csv`) with URL features and corresponding labels.
- **Training**: Fine-tunes BERT for sequence classification on the dataset.
- **Evaluation**: Assesses model accuracy and generates a classification report on a test set.
- **Usage**: Provides a function `classify_url(url)` for real-time URL classification.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, transformers, torch

## Example
```python
url = "example.com"
classification = classify_url(url)
print(f"The URL '{url}' is classified as: {classification}")
