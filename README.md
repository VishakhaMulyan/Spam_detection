# Spam_detection
# Spam Detection using Machine Learning (98% Accuracy)
This project is a simple yet powerful *Spam Detection System* built using Machine Learning (Naive Bayes classifier) with *98% accuracy*.

## 🚀 Features
- Detects whether a message is *Spam* or *Ham (Not Spam)*
- Achieved *98% accuracy* using Naive Bayes
- Uses *CountVectorizer* for text vectorization
- Trained and tested on real SMS spam dataset

## 🛠️ Technologies Used
- Python
- Scikit-learn
- Pandas
- Google Colab
- GitHub

## 📂 Files in this Repo
- spam_detection_model.pkl ➔ Saved trained model
- vectorizer.pkl ➔ Saved vectorizer for transforming new messages
- spam_detection_project.ipynb ➔ Colab notebook with full code

## 🔥 How to Use
1. Load the trained model and vectorizer
2. Call the predict_spam() function with your message
3. Get instant result: "Spam" or "Ham"

## ✅ Example:
```python
print(predict_spam("Congratulations! You have won a free ticket."))
# Output: Spam
