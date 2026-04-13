# Breast Cancer Classification using ANN

## Project Overview
This project applies Artificial Neural Networks (ANN) to classify breast cancer tumors as Malignant or Benign using supervised machine learning techniques.

The goal is to test multiple ANN architectures and compare their performance to select the best model.

---

## Dataset

The dataset used in this project is Breast Cancer Classification Dataset

### Dataset Information

- Number of Samples: 569  
- Number of Features: 30  
- Target Column: diagnosis  

### Target Values

- M → Malignant  
- B → Benign  

---

## Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- NumPy  
- Google Colab  

---

## Model Used

Artificial Neural Network using:

MLPClassifier

---

## Experiments

| Experiment | Hidden Layers | Max Iter | Accuracy |
|------------|---------------|----------|----------|
| 1 | (30,) | 300 | 95.6% |
| 2 | (50,) | 500 | 96.5% |
| 3 | (100,) | 800 | 93.9% |
| 4 | (50,50) | 1000 | 95.6% |

---

## Best Model

Best Model:

- Hidden Layers: (50,)  
- Max Iterations: 500  
- Accuracy: 96.5%

This model achieved the highest performance.

---

## Project Structure

```
experiments.ipynb
breast_cancer_classification.csv
smart system report.pdf
README.md
```

---

## Conclusion

Artificial Neural Networks were successfully applied to classify breast cancer data.  
Multiple configurations were tested, and the best model achieved 96.5% accuracy.

This project demonstrates the importance of model tuning and experimentation.

---

## Author

Anas Mostafa  
Alexandria National University  
Smart Systems Course
