# 🏥 Healthcare Symptom Checker Chatbot

A Python-based chatbot that predicts possible diseases based on user-described symptoms using Machine Learning.

---

## 📌 Features

- Natural language symptom input
- Multi-layer symptom extraction (synonym mapping, exact match, fuzzy matching)
- Disease prediction using Random Forest Classifier
- Dynamic follow-up questions based on predicted disease
- Confidence score for each prediction
- Disease description and precaution suggestions

---

## 🛠️ Tech Stack

- **Language:** Python
- **ML Model:** Random Forest Classifier
- **Libraries:** Scikit-learn, Pandas, NumPy
- **NLP:** difflib (fuzzy matching), regex

---

## 📁 Project Structure

```
├── Data/
│   ├── Training.csv
│   └── Testing.csv
├── MasterData/
│   ├── symptom_Description.csv
│   ├── symptom_severity.csv
│   └── symptom_precaution.csv
├── chatbot.py
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository
```bash
git clone https://github.com/deepsanbui08/healthcare-chatbot.git
cd healthcare-chatbot
```

2. Install dependencies
```bash
pip install scikit-learn pandas numpy
```

3. Run the chatbot
```bash
python chatbot.py
```

---

## 💬 How It Works

1. User enters their name, age, and gender
2. User describes symptoms in a natural sentence
3. Chatbot extracts symptoms using synonym mapping, exact matching, and fuzzy matching
4. Initial disease prediction is made using Random Forest
5. Chatbot asks disease-specific follow-up questions
6. Final prediction is shown with confidence score, description, and precautions

---

## 📊 Dataset

- **Training.csv** — symptom-disease mapping used to train the model
- **Testing.csv** — used for model evaluation
- **symptom_Description.csv** — disease descriptions
- **symptom_severity.csv** — severity weights for each symptom
- **symptom_precaution.csv** — precautions for each disease

---

## ⚠️ Disclaimer

This chatbot is for educational purposes only and is not a substitute for professional medical advice. Always consult a qualified doctor for medical decisions.

---

## 👨‍💻 Author

**Deep Sanbui**
[GitHub](https://github.com/deepsanbui08) | [LinkedIn](https://www.linkedin.com/in/deep-sanbui-699814254)
