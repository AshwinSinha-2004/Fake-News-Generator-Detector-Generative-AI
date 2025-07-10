# 📰 Fake News Generator & Detector Generative AI

The project builds a Generative-AI system that generates fake news headlines using GPT-2 and detects them using a text classification model like BERT.
A demonstration system showcasing both the creative power and ethical responsibility of generative AI. 

This project:
- **Generates** plausible “fake” news headlines by fine‑tuning GPT‑2.
- **Detects** real versus fake headlines using a BERT‑based classifier.
- Provides a simple command‑line or Colab interface for experimentation.

---

## 🚀 Features

- **GPT‑2 Headline Generator**  
  • Fine‑tune on real news headlines  
  • Sample new, synthetic headlines  
- **BERT Detector**  
  • Binary classification (REAL vs. FAKE)  
  • Train on balanced True_News.csv and Fake_News.csv  
- **Easy Experimentation**  
  • Run locally or in Google Colab  
  • Script handles data loading, training, and inference  

---

## 📋 Requirements

- Python 3.8+  
- `transformers`  
- `torch`  
- `scikit-learn`  
- `pandas`  
- `numpy`  
- `nltk`  
- `gradio`  

---

## 🔧 Installation (Local)

1. **Clone the repository**  
   ```bash
   git clone https://github.com/https:/AshwinSinha-2004/Fake-News-AI.git
   cd Fake-News-AI

2. **Create and activate a virtual environment**
    python3 -m venv venv
    source venv/bin/activate

3. **Install dependencies**
    pip install -r requirements.txt

---

## ☁️ Running in Google Colab

1. Upload True_News.csv and Fake_News.csv to your Colab session.

2. **In a notebook cell, install packages:**
    !pip install -r requirements.txt

3. **Execute the main script:**
    !python Fake_News_Generator_&_Detector_Using_Generative_AI_&_NLP.py

4. Follow the on‑screen prompts or Gradio link.

---

