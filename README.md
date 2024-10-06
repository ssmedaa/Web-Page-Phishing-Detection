# Web Page Phishing Detection
## Description
Supervised machine learning algorithm that supplies a set of datasets for training purposes to detect phishing web pages. 

## Dataset
- [Kaggle: Web Page Dataset](https://www.kaggle.com/datasets/shashwatwork/web-page-phishing-detection-dataset/data).
  - Number of data sample: 11,430 website URLs
  ## Data Preparation
  - 23 features
    -  Cleaning to keep important features: **ip address** and **status** (legitimate site or phishing) in binary form.
   
## Data Training and Model 
- Decision Tree model for prediction modeling of websites
- Split:
  1. Training 70%
  2. Testing 15%
  3. Validation 15%

 ## Evaluation
 | | precision | recall | f1-score |
 | --- | --- | --- | ---|
 | **0** | 0.91 | 0.92 | 0.91 |
 | **1** | 0.92 | 0.91 | 0.92 |
 |||||
 | **accuracy**| | | 0.92|

 ```
False Positive Rate (FPR): 0.0799
False Negative Rate (FNR): 0.0886
```

```math
Confusion Matrix:
\begin{bmatrix}1555&135\\154&1585\\\end{bmatrix}
  ```

   
    
