# Sentimen Analysis

This is a real-time sentiment analysis app built using a fine-tuned BERT model on Amazon product reviews. The app classifies text into **Positive**, **Neutral**, or **Negative** categories and gives confidence scores for transparency. Developed with **Gradio** and deployed on **Hugging Face Spaces**.

---

## 🚀 Objective

To build and deploy an end-to-end NLP solution that allows users to analyze the sentiment of written product reviews. The app also collects feedback for future model improvements.

---

## 🧠 Model & Dataset

- **Model**: BERT (`bert-base-uncased`)
- **Fine-tuned on**: A balanced subset of **104,958 Amazon product reviews**
- **Training Framework**: PyTorch with Hugging Face Transformers
- **Class Labels**:
  - `0`: Negative
  - `1`: Neutral
  - `2`: Positive

---

## 📊 Performance

| Set        | Accuracy | F1 Score |
|------------|----------|----------|
| Training   | 90.44%   | 90.50%   |
| Validation | 83.18%   | 83.34%   |
| Test       | 82.88%   | 82.99%   |

---

## 🖥️ Features

- 📍 Sentiment prediction with confidence score
- 📊 Label output: *Positive*, *Neutral*, *Negative*
- 📝 Real-time user feedback collection
- 🎨 Colored label display for intuitive UI
- 🧪 Example review inputs
- 💬 Textbox-based input for free-form reviews

---

## 🧰 Tech Stack

- Python 🐍
- BERT (Hugging Face Transformers)
- PyTorch
- Datasets (Hugging Face)
- Gradio
- Google Colab (for training)
- Hugging Face Spaces (for deployment)
- 

## Here is the link to the Hugging Face Space (https://huggingface.co/spaces/LeemahLee/Sentiment-Analysis) for you to try

## 🛠️ How to Use

1. Type a product review in the text box.
2. Click "Submit" to see the sentiment and confidence.
3. Optionally, give feedback on whether the prediction was correct.

---

## 📝 Feedback Logging

Feedback (correct/incorrect) is stored in a local CSV file named `user_feedback.csv`. This helps track model performance and can be used for future retraining.


