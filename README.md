# Natural-Language-Processing-with-Disaster-Tweets
## BİL 470 Projesi Natural Language Processing with Disaster Tweets
[Kaggle linki](https://www.kaggle.com/c/nlp-getting-started/overview)  
Kullanılan Modeller
* Logistic Regression (Unigram, Bigram ve ikisi birlikte)
* Naive Bayes (Unigram, Bigram ve ikisi birlikte)
* SVC OneVsRestClassifier (Unigram, Bigram ve ikisi birlikte)
* fasttext Bigram 
* BERT
* RoBERTa  

## Sonuçlar
Logistic Regression
[[779  95]
 [212 437]]
              precision    recall  f1-score   support

           0       0.79      0.89      0.84       874
           1       0.82      0.67      0.74       649

    accuracy                           0.80      1523
   macro avg       0.80      0.78      0.79      1523
weighted avg       0.80      0.80      0.79      1523

Naive Bayes
[[787  87]
 [226 423]]
              precision    recall  f1-score   support

           0       0.78      0.90      0.83       874
           1       0.83      0.65      0.73       649

    accuracy                           0.79      1523
   macro avg       0.80      0.78      0.78      1523
weighted avg       0.80      0.79      0.79      1523

SVC
[[781  93]
 [208 441]]
              precision    recall  f1-score   support

           0       0.79      0.89      0.84       874
           1       0.83      0.68      0.75       649

    accuracy                           0.80      1523
   macro avg       0.81      0.79      0.79      1523
weighted avg       0.81      0.80      0.80      1523

fasttext
[[884  62]
 [269 308]]
              precision    recall  f1-score   support

           0       0.77      0.93      0.84       946
           1       0.83      0.53      0.65       577

    accuracy                           0.78      1523
   macro avg       0.80      0.73      0.75      1523
weighted avg       0.79      0.78      0.77      1523

Bert
[[790  78]
 [160 495]]
              precision    recall  f1-score   support

           0       0.83      0.91      0.87       868
           1       0.86      0.76      0.81       655

    accuracy                           0.84      1523
   macro avg       0.85      0.83      0.84      1523
weighted avg       0.85      0.84      0.84      1523

Roberta
[[773 118]
 [153 479]]
              precision    recall  f1-score   support

           0       0.83      0.87      0.85       891
           1       0.80      0.76      0.78       632

    accuracy                           0.82      1523
   macro avg       0.82      0.81      0.82      1523
weighted avg       0.82      0.82      0.82      1523
