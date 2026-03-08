[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18BafE-2f7kYuTmjYCvhkKLE_vv2Syhvy#scrollTo=PflWc31Sq9BA)
# NLP Model Comparison on IMDb Sentiment Dataset

This project compares three NLP models for sentiment analysis using the IMDb movie review dataset.

## Models Used
- Logistic Regression (Scikit-learn)
- LSTM (Keras)
- BERT (Hugging Face Transformers + PyTorch)

## Dataset
IMDb Movie Reviews Dataset (Binary Sentiment Classification)

## Experiments Performed
- Model training and evaluation
- Confusion matrix analysis
- Precision, Recall, F1-score comparison
- Training time comparison
- Accuracy comparison visualization
- Error analysis
- Noise robustness experiment

## Results

| Model | Accuracy |
|------|------|
| Logistic Regression | 0.8748 |
| LSTM | 0.829 |
| BERT | 0.8908 |

BERT achieved the highest accuracy, while Logistic Regression performed surprisingly well with lower training time.

## Notebook
The full experiment can be found in:

`nlp_model_comparison.ipynb`

## Tools & Libraries
- Python
- Scikit-learn
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers
- Matplotlib / Seaborn

## Author
Apooja
