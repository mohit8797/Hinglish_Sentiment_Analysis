#Hinglish Sentiment Analysis 

This project focuses on building a sentiment classification system for Hinglish (Hindi + English code-mixed) text using modern NLP techniques. The goal is to classify text into Positive, Neutral, or Negative sentiments using deep learning and transformer-based models.

✨ Key Features
	•	Hinglish dataset preprocessing (cleaning, label encoding, tokenization)
	•	Multiple model implementations:
	•	BiLSTM
	•	CNN + LSTM
	•	mBERT (Multilingual BERT)
	•	XLM-RoBERTa (Final best-performing model)
	•	Model training using Hugging Face Transformers
	•	Evaluation metrics: Accuracy, F1-Score, Confusion Matrix
	•	Inference pipeline for real-time sentiment prediction

📊 Dataset
	•	Source: Kaggle – Hinglish Sentiment Dataset
	•	Total samples: 2766
	•	Labels: Negative (0), Neutral (1), Positive (2)

🏆 Final Results
	•	Best Model: XLM-RoBERTa
	•	Accuracy: 66%
	•	Weighted F1 Score: 0.59

🔧 Tech Stack
	•	Python
	•	PyTorch
	•	Hugging Face Transformers
	•	Scikit-Learn
	•	Pandas / NumPy
	•	Matplotlib / Seaborn

📦 How to Run - just run ipynb file
