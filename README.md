# 📰 News Topic Classifier (BERT)

A simple but powerful NLP project where I fine-tuned a BERT model to classify news headlines into categories like **World, Sports, Business, and Sci/Tech**.

Built as part of my AI/ML learning + internship work — focused on understanding how transformer models actually perform in real tasks.

---

## 💡 What this project does
You give it a news headline, and it predicts what category it belongs to.

Example:
- "Pakistan wins cricket world cup final" → 🏅 Sports  
- "Apple launches new AI-powered iPhone" → 🔬 Sci/Tech  

---

## ⚙️ How it works (simple explanation)
- Uses a pre-trained **BERT model**
- Fine-tuned on the **AG News dataset**
- Converts text → tokens → predictions
- Outputs probabilities for each category

---

## 🛠️ Tech used
- Python  
- PyTorch  
- Hugging Face Transformers  
- Datasets  
- Gradio (for UI)

---

## 📂 Dataset
Using the **AG News dataset** (via Hugging Face), which has 4 categories:
- World  
- Sports  
- Business  
- Sci/Tech  

---

## 🚀 Running the project

### 1. Install dependencies
```bash
pip install transformers datasets evaluate accelerate gradio
```

### 2. Run the script
```bash
python main.py
```

Or run it in **Google Colab** (recommended if you don’t have GPU).

---

## 🧪 Demo
The project includes a **Gradio interface**, so after running you’ll get a link like:

```
https://xxxx.gradio.live
```

Paste any headline and see predictions instantly.

---

## 📊 Results
On a smaller training subset (for speed):
- Accuracy ≈ **90%+**
- F1 Score ≈ **0.90**

(Not perfect, but pretty solid for a quick fine-tune)

---

## 🔍 Example inputs
Try these:
- Pakistan wins cricket world cup final against India  
- Stock market crashes after economic data  
- Scientists discover new planet  
- Apple releases new AI features  

---

## 🧠 What I learned
- How BERT tokenization actually works  
- Fine-tuning transformers using Hugging Face Trainer  
- Handling datasets + evaluation metrics  
- Building a quick ML demo using Gradio  

---

## 🚧 Future improvements
- Train on full dataset (better accuracy)  
- Try other models like DistilBERT / RoBERTa  
- Save & reuse trained model  
- Deploy as an API  

---

## 👨‍💻 About me
Subhan — AI/ML student exploring real-world projects and building practical skills.

---

## ⭐ If you like this
Feel free to star the repo or suggest improvements!
