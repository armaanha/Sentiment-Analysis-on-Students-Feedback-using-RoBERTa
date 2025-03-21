#  Sentiment Analysis on Students' Feedback using RoBERTa

## 📌 Project Overview
This project leverages the **RoBERTa** model to analyze students' course feedback and classify sentiments into **positive, negative, or neutral** categories. The insights gained can help instructors and institutions improve course content and teaching methods.

## 🏗 Approach & Model
- **Model Used:** RoBERTa, Vader
- **Sentiment Labels:** Positive, Negative, Neutral
<img width="345" alt="image" src="https://github.com/user-attachments/assets/caa3b0f8-b110-4630-b790-30bd8be0ff2e" />

- **Libraries Used:** `nltk`, `transformers`, `torch`, `pandas`, `numpy`, `scipy`, `tqdm` 
- **Input:** [Student feedback text](https://www.kaggle.com/datasets/tilorc/rate-my-professor-reviews-5c-colleges?resource=download) (unstructured JSON file)
- **Output:** Sentiment classification & confidence scores from a transformer pipeline

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/sentiment-analysis-roberta.git
cd sentiment-analysis-roberta
