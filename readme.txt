# 🧠 ReasonBench

> Evaluating AI reasoning with machine learning and adaptive memory.

ReasonBench is an AI evaluation framework that predicts whether large language model (LLM) reasoning is correct by combining semantic text features with structured machine learning models. Instead of trusting AI outputs blindly, the system estimates reasoning reliability and learns from previous mistakes through an adaptive memory mechanism.

---

## 🚀 Features

- Predicts correctness of AI-generated reasoning
- TF-IDF semantic feature extraction
- XGBoost classification model
- Adaptive memory for continuous learning
- Interactive command-line testing
- Lightweight and extensible architecture

---

## 🏗️ Workflow

```
LLM Response
      │
      ▼
TF-IDF Feature Extraction
      │
      ▼
XGBoost Classifier
      │
      ▼
Confidence Prediction
      │
      ▼
Adaptive Memory
      │
      ▼
Final Evaluation
```

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- XGBoost
- Pandas
- NumPy

---

## 📈 Results

- Accuracy: ~90%
- Balanced Precision & Recall
- Improved from ~85% to ~90% using semantic TF-IDF features

---

## ▶️ Getting Started

```bash
pip install -r requirements.txt

python src/train.py

python src/app.py
```

---

## 💡 Key Insight

ReasonBench demonstrates that longer or more detailed AI responses are not necessarily more accurate. By learning semantic patterns associated with incorrect reasoning, the system improves trust and reliability in LLM-generated outputs.

---

## 📄 License

MIT License
