# 🎭 Multimodal Emotion Recognition
> Combining Facial Emotion Recognition + Text Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.12-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview
This project builds a multimodal emotion recognition system that:
- 🖼️ Detects emotion from facial images using a CNN trained on FER2013
- 📝 Analyzes sentiment from text using VADER
- 🔀 Fuses both using Rule-based and ML-based fusion

---

## 📁 Project Structure
```
multimodal-emotion-recognition/
├── notebooks/
│   └── Multimodal_Emotion_Recognition.ipynb
├── app/
│   └── emotion_app.py
├── sample_images/
├── models/
├── requirements.txt
└── README.md
```

---

## 🗂️ Dataset
- FER2013 — 35,887 grayscale 48×48 face images
- 7 classes: angry · disgust · fear · happy · sad · surprise · neutral
- Download: [Kaggle FER2013](https://www.kaggle.com/datasets/deadskull7/fer2013)

---

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/multimodal-emotion-recognition.git
cd multimodal-emotion-recognition
pip install -r requirements.txt
```

---

## 🚀 How to Run

### Google Colab (Recommended)
1. Open `notebooks/Multimodal_Emotion_Recognition.ipynb` in Colab
2. Set runtime to GPU → T4
3. Run all cells

### Streamlit App
```bash
streamlit run app/emotion_app.py
```

---

## 📊 Results
| Metric | Score |
|--------|-------|
| Accuracy | ~65% |
| Precision | ~64% |
| Recall | ~65% |
| F1 Score | ~64% |

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| TensorFlow/Keras | CNN model |
| OpenCV | Face detection |
| NLTK + VADER | Sentiment analysis |
| Scikit-learn | Evaluation metrics |
| Streamlit | Web interface |

---

## 🖼️ Sample Output
```
🖼️  Face Emotion  : happy      (91.23%)
📝  Text Sent.   : positive   (compound=0.689)
✅  Final Emotion : happy
```

---
