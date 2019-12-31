# name-that-genre
Embedding + CNN model to classify music genre based on lyrics

Current winning model is shown below

![Model](https://github.com/Kobai/name-that-genre/blob/master/model.png)

Models scores are shown below
```
label       precision  recall   f1-score   support

Pop             0.59      0.49      0.54      6169
Hip-Hop         0.79      0.80      0.79      2971
Rock            0.59      0.72      0.65      9524
Metal           0.76      0.65      0.70      4098
Country         0.61      0.49      0.54      2644

accuracy                            0.64     25406
macro avg       0.67      0.63      0.64     25406
weighted avg    0.64      0.64      0.64     25406
```

Confusion Matrix shown below

![cm](https://github.com/Kobai/name-that-genre/blob/master/cm.PNG)