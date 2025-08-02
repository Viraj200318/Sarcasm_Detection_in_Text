## Sarcasm Detection using NLP (TF-IDF + Logistic Regression)

##  **README.md – Sarcasm Detection using NLP**

### **Project Overview**

This project is a **basic sarcasm detection model** built using **Natural Language Processing (NLP)** techniques.
It classifies text headlines into **sarcastic (😏)** or **not sarcastic (🙂)** using a **Logistic Regression model** trained on the popular **News Headlines Dataset for Sarcasm Detection**.

The model uses:

* **TF-IDF Vectorization** – Converts text into numerical features.
* **Logistic Regression** – A simple, interpretable machine learning model.
* **Scikit-learn** – For model training and evaluation.

---

###  **Dataset**

* **Source:** [Kaggle – News Headlines Dataset for Sarcasm Detection](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection)
* **Format:** JSON file with the following fields:

  * `headline` → The text headline
  * `is_sarcastic` → **1 = sarcastic**, **0 = not sarcastic**



### ⚙ **Installation & Setup**

```bash
# 1️ Clone the repository
git clone https://github.com/yourusername/sarcasm-detector.git
cd sarcasm-detector

# 2️ Install dependencies
pip install pandas scikit-learn
```

---

### 🚀 **How to Run**

```bash
python sarcasm_detector.py
```

The script will:
✅ Load and preprocess the dataset
✅ Train a Logistic Regression model
✅ Evaluate accuracy
✅ Predict sarcasm on custom text





####  **Model Accuracy**


 Accuracy: 0.82



####  **Custom Predictions(OUTPUTS)**


 "Oh great, another Monday morning!" → 😏 Sarcastic
 "I had a fantastic vacation!" → 🙂 Not Sarcastic
 "Yeah right, like I have time for that." → 😏 Sarcastic


### **Project Structure**


sarcasm-detector/

sarcasm_detector.py       # Main Python script 
 Sarcasm_Headlines_Dataset.json  # Dataset file
 README.md                 # Project documentation


###  **Future Improvements**

✅ Try **Naive Bayes** or **SVM** models for comparison
✅ Use **transformers (BERT)** for higher accuracy
✅ Handle **code-mixed (Hinglish) sarcasm**
✅ Build a **web interface (Streamlit or Flask)** for real-time sarcasm detection



