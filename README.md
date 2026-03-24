# 📊 Web Mining

Repozitorijum namenjen za potrebe projekta iz predmeta **Web Mining**.  
Cilj projekta je poređenje performansi modela mašinskog i dubokog učenja za analizu sentimenta, sa fokusom na **generalizaciju u uslovima promene domena (domain shift)**.

---

## 📂 Skupovi podataka

- **Yelp Reviews**  
  [Yelp Reviews Sentiment Dataset & Code](https://www.kaggle.com/datasets/thedevastator/yelp-reviews-sentiment-dataset/data)

- **Amazon Reviews**  
  [Amazon Reviews for Sentiment Analysis (Binary)](https://www.kaggle.com/datasets/yacharki/amazon-reviews-for-sa-binary-negative-positive-csv)

---

## 📊 Opis podataka

- **Yelp**
  - 560.000 trening uzoraka  
  - 38.000 test uzoraka  
  - Balansirane klase (1:1)  

- **Amazon**
  - Smanjen (subsampling) na veličinu Yelp skupa  
  - 560.000 trening uzoraka  
  - 38.000 test uzoraka  
  - Nebalansirane klase (2:3)  

---

## 🤖 Metode mašinskog učenja

- Logistic Regression  
- Linear SVM  
- Naive Bayes  
- Passive-Aggressive Classifier  

---

## 🧠 Metode dubokog učenja

- TextCNN  
- BiLSTM  
- BERT (pretreniran)  
- BERT (fine-tuned)

---

## 🔄 Eksperimenti

- Evaluacija na istom domenu  
  - Yelp → Yelp  
  - Amazon → Amazon  

- Evaluacija sa promenom domena  
  - Yelp → Amazon  
  - Amazon → Yelp  

---

## 🎯 Cilj

Poređenje ML i DL modela u zadatku analize sentimenta i analiza njihove robusnosti pri promeni domena.