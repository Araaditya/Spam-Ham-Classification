📌 SMS Spam–Ham Classification Dataset

📖 Overview

The **SMS Spam–Ham Classification Dataset** contains **5,574 SMS messages**, each labeled as either:

* **Ham** → Legitimate / normal message
* **Spam** → Unwanted / promotional message

This dataset is widely used for **text classification**, **spam filtering**, and **NLP model evaluation**.

---

📊 Dataset Summary

| Label     | Count     | Percentage |
| --------- | --------- | ---------- |
| Ham       | 4,827     | 86.6%      |
| Spam      | 747       | 13.4%      |
| **Total** | **5,574** | **100%**   |

---

Format

* Each line contains:

  1. **Label** → `ham` or `spam`
  2. **Message text** → Raw SMS content

Example:

```
ham   What you doing? How are you?  
ham   Ok lar... Joking wif u oni...  
spam  FreeMsg: CALL to No: 86888 & claim your reward...  
spam  URGENT! Your Mobile No 07808726822 was awarded a bonus...  
```

🛠️ Usage

This dataset can be used for:

* Building **spam detection models**.
* Experimenting with **NLP techniques** (tokenization, TF-IDF, embeddings).
* Benchmarking ML algorithms such as:

  * Naive Bayes
  * SVM
  * Random Forest
  * Deep Learning models

---

🌍 Applications
* **SMS Spam Filtering** on mobile devices.
* **Email Spam Detection** (conceptually similar).
* **Text Mining & NLP Research**.
