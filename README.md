# 🧠 social-media-sentiment-analysis-roberta

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge&logo=pytorch)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange?style=for-the-badge&logo=googlecolab)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📌 Project Overview

This project implements **Sentiment Analysis** using the pretrained **CardiffNLP Twitter RoBERTa Transformer** model. The system classifies social media text into **Positive**, **Neutral**, and **Negative** sentiments using Natural Language Processing (NLP) techniques.

A custom dataset containing **600 sentiment-labelled samples** was created and used to evaluate the model. Performance was measured using standard classification metrics including Accuracy, Precision, Recall, F1-score, and a Confusion Matrix.

---

## 🎯 Objectives

- Build a sentiment analysis system using a Transformer-based language model.
- Understand how pretrained NLP models can be applied to real-world text.
- Evaluate model performance on a custom dataset.
- Visualize prediction results using graphs and performance metrics.
- Demonstrate the practical application of Natural Language Processing.

---

## 🚀 Features

- Pretrained RoBERTa Transformer model
- Twitter-specific sentiment classification
- Custom dataset (600 samples)
- Text preprocessing
- Batch prediction
- Accuracy evaluation
- Precision, Recall & F1-score
- Confusion Matrix
- Bar Chart visualization
- Pie Chart visualization
- Google Colab implementation

---

## 🧰 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Google Colab | Development Environment |
| Hugging Face Transformers | Pretrained Transformer Model |
| PyTorch | Deep Learning Framework |
| Pandas | Data Handling |
| NumPy | Numerical Computation |
| Scikit-learn | Performance Evaluation |
| Matplotlib | Data Visualization |
| OpenPyXL | Excel File Handling |
| SciPy | Softmax Function |

---

## 🤖 Model Used

**Model Name**

```text
cardiffnlp/twitter-roberta-base-sentiment-latest
```

The model is a pretrained RoBERTa Transformer developed by CardiffNLP for sentiment analysis on Twitter and social media text. It predicts one of three sentiment classes:

- Positive
- Neutral
- Negative

---

## 📊 Dataset

A **custom dataset of 600 samples** was created for this project.

| Sentiment | Samples |
|-----------|---------|
| Positive | 200 |
| Neutral | 200 |
| Negative | 200 |
| Total | 600 |

Each sample contains:

- Text
- Sentiment Label
- Numeric Label

---

## ⚙️ Project Workflow

```text
Input Text
      │
      ▼
Text Preprocessing
      │
      ▼
RoBERTa Tokenizer
      │
      ▼
RoBERTa Transformer Model
      │
      ▼
Softmax Probability
      │
      ▼
Sentiment Prediction
      │
      ▼
Performance Evaluation
      │
      ▼
Visualization
```

---

## 📈 Performance Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Overall Accuracy

**79.83%**

The model achieved strong performance in identifying **Positive** and **Negative** sentiments. Neutral sentiment was comparatively more challenging because neutral text often lacks strong emotional cues.

---

## 📂 Project Structure

```text
Twitter-Sentiment-Analysis/

│── notebook/
│     └── Twitter_Sentiment_Analysis_using_RoBERTa_Transformer.ipynb
│
│── dataset/
│     ├── custom_social_media_sentiment_dataset_600.xlsx
│     └── Prediction_Output.xlsx
│
│── images/
│     ├── confusion_matrix.png
│     ├── sentiment_bar_chart.png
│     └── sentiment_pie_chart.png
│
│── README.md
│── requirements.txt
│── LICENSE
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone <repository-link>
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Open the notebook using Google Colab or Jupyter Notebook.

4. Run all cells sequentially.

---

## 📌 Results

- Successfully classified sentiment into three categories.
- Achieved approximately **79.83%** overall accuracy on the custom dataset.
- Generated prediction outputs and performance visualizations.
- Demonstrated the effectiveness of Transformer-based NLP for sentiment analysis.

---

## 🔮 Future Enhancements

- Fine-tune the RoBERTa model on the custom dataset.
- Deploy the project using Streamlit or Flask.
- Support multilingual sentiment analysis.
- Integrate real-time Twitter/X data using APIs.
- Improve neutral sentiment detection.

---

## 📚 References

1. Camacho-Collados et al., *TweetNLP: Cutting-Edge Natural Language Processing for Social Media*, EMNLP 2022.

2. Loureiro et al., *TimeLMs: Diachronic Language Models from Twitter*, ACL 2022.

3. Hugging Face Model:
https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest

---

## 👩‍💻 Author

**Yukti Dubey**

B.Tech – Robotics & Artificial Intelligence

DIT University

---

⭐ If you found this project useful, consider giving it a star!
