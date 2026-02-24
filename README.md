# **Title: Selection of Best Pre-Trained Model for Text Classification using TOPSIS**

---

## **1. Methodology**

```
Model Selection → Criteria Identification → Decision Matrix Formation
→ Normalization → Weighted Normalized Matrix
→ Ideal Best & Ideal Worst Solution
→ Distance Calculation → TOPSIS Score
→ Model Ranking → Result Analysis
```

---

## **2. Description**

* Task: Text Classification
* Number of Models Compared = 5
* Models Used:

  * BERT-base
  * RoBERTa-base
  * DistilBERT
  * XLNet-base
  * MobileBERT

### **Decision Criteria Used**

* Accuracy (%)
* F1 Score
* Inference Time (ms)
* Model Size (MB)
* Training Time (hrs)

### **Criteria Type**

* Benefit Criteria → Accuracy, F1 Score
* Cost Criteria → Inference Time, Model Size, Training Time

---

## **3. Input / Output**

### **Decision Matrix**

The performance of different pre-trained transformer models was evaluated based on the above criteria and used as input to the TOPSIS algorithm implemented in Python.

---

### **TOPSIS Result**

| Model        | TOPSIS Score | Rank |
| ------------ | ------------ | ---- |
| MobileBERT   | 0.930298     | 1    |
| DistilBERT   | 0.824273     | 2    |
| BERT-base    | 0.372889     | 3    |
| RoBERTa-base | 0.296870     | 4    |
| XLNet-base   | 0.062122     | 5    |

✔ Best Model Selected = **MobileBERT**

---

## **4. Performance Graph**

Bar graph representing TOPSIS scores of all models was generated using matplotlib for comparative analysis.

<img width="567" height="500" alt="image" src="https://github.com/user-attachments/assets/f9b3fc06-7392-4685-b377-6f8bbde48211" />


---

## **5. Tools & Technologies Used**

* Python
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

---

## **6. Conclusion**

Using the TOPSIS multi-criteria decision making technique, **MobileBERT** was identified as the most suitable pre-trained model for text classification tasks. It achieves the best balance between performance metrics such as accuracy and F1 score along with computational efficiency such as smaller model size and faster inference time.



---

## **7. References**

* HuggingFace Transformers Documentation
* Multi-Criteria Decision Making Methods
* TOPSIS Methodology

---
