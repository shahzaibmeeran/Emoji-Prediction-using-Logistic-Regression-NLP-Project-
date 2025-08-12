# emoji-text-classifier

A simple NLP-based text classification project that predicts the most appropriate emoji for a given sentence.

## 📌 Features
- Preprocesses text (lowercasing, punctuation removal)
- Converts text into numerical format using **TF-IDF Vectorization**
- Trains a **Logistic Regression** model
- Evaluates accuracy and displays a **confusion matrix**
- Predicts emojis for custom input sentences

## 📂 Dataset
The dataset contains 100+ rows of sentences with corresponding emoji labels.  
Example:

| Sentence                 | Emoji |
|--------------------------|-------|
| I am feeling happy today | 😊    |
| I miss my family         | 😢    |
| That was so funny        | 😂    |

# 📷 Example Predictions

I love programming! → ❤️
I'm feeling sleepy → 😴
That was so funny! → 😂
I miss my family → 😢
This is unbelievable → 😱

# 📊 Model Performance
Accuracy: 1.0
