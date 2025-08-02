# AI Mood Detector 🎭

This project predicts the **mood** (Positive, Neutral, or Negative) of any sentence using a simple AI model trained on text data.

---

## 🚀 Features
- Detects **Positive**, **Negative**, and **Neutral** moods.
- Easy to run in **Google Colab** – no setup required.
- Built using **Python**, **pandas**, and **scikit-learn** (Naive Bayes).

---

## 📂 Project Structure
- **mood_model.ipynb** → Jupyter/Colab notebook with the AI code.
- **mood_data.csv** → Dataset of sample sentences with their moods.
- **README.md** → Project guide (this file).

---

## ▶️ How to Run
1. Open `mood_model.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Upload the `mood_data.csv` file using Colab’s file upload.
3. Run all the cells in order (Shift + Enter).
4. Change the `user_input` in the code to test your own sentences.

Example:
```python
user_input = ["I am happy!"]
ouput:
Mood detected: Positive
