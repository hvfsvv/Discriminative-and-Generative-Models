# Discriminative vs. Generative Models - Naïve Bayes Classification

##  Overview
This repository contains two Jupyter notebooks that explore **Discriminative and Generative Models** using **Naïve Bayes Classification**. The goal is to compare these approaches for text classification tasks such as **spam detection**.

- `Pre-Lab_Discriminative_and_Generative_Models.ipynb`: Introduction to the theoretical concepts behind **discriminative** and **generative models**.
- `lab4.ipynb`: Practical implementation of **Naïve Bayes classifiers** (Bernoulli, Multinomial, and Gaussian) applied to real-world datasets.

## Files in This Repository
| File | Description |
|------|------------|
| `Pre-Lab_Discriminative_and_Generative_Models.ipynb` | Pre-lab notebook covering the **mathematical foundations** and **theory** behind discriminative vs. generative models. |
| `lab4.ipynb` | Hands-on implementation of **Naïve Bayes classifiers** to classify spam emails, including performance evaluation metrics. |

---

## Getting Started

### **1️ Installation**
First, ensure you have Python and the required libraries installed. You can install them using:

```bash
pip install numpy pandas scikit-learn matplotlib notebook
```

### **2️ Run Jupyter Notebook**
To open the notebooks, navigate to the project folder and run:

```bash
jupyter notebook
```

Then, open either:
- `Pre-Lab_Discriminative_and_Generative_Models.ipynb`
- `lab4.ipynb`

---

##  Understanding the Concepts

### **1️ Discriminative vs. Generative Models**
| Model Type | What It Does | Example |
|------------|-------------|---------|
| **Generative Model** | Learns how the data is generated, modeling \( P(X | y) \) | **Naïve Bayes (Gaussian, Multinomial, Bernoulli)** |
| **Discriminative Model** | Learns a direct decision boundary between classes \( P(y | X) \) | **Logistic Regression, SVM** |

### **2️ Types of Naïve Bayes Implemented**
| Naïve Bayes Type | Used For | Data Type |
|------------------|---------|-----------|
| **BernoulliNB** | Binary text classification (Spam detection) | **Binary (0/1: Word Presence)** |
| **MultinomialNB** | NLP tasks like document classification | **Word frequencies** |
| **GaussianNB** | Continuous data (e.g., medical diagnoses) | **Real numbers (Height, Weight, etc.)** |

---

## Performance Metrics
Each classifier is evaluated using:
- **Accuracy**: \( \frac{TP + TN}{TP + TN + FP + FN} \)
- **Precision**: \( \frac{TP}{TP + FP} \)
- **Recall (Sensitivity)**: \( \frac{TP}{TP + FN} \)
- **F1 Score**: \( 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}} \)

---

## Results & Observations
- **Naïve Bayes performs well for text classification tasks like spam filtering.**
- **MultinomialNB is better suited for word frequency-based classification.**
- **GaussianNB is useful for continuous numerical features but not ideal for NLP.**
- **Discriminative models like logistic regression often outperform Naïve Bayes for complex datasets.**

---

##  How to Contribute
1. **Fork this repository** 
2. **Clone it to your local machine**:  
   ```bash
   git clone https://github.com/your-username/Discriminative-vs-Generative-Models.git
   ```
3. **Create a new branch**:  
   ```bash
   git checkout -b feature-improvement
   ```
4. **Make your changes & commit**:
   ```bash
   git commit -m "Improved performance by tuning alpha in Naïve Bayes"
   ```
5. **Push to GitHub & submit a pull request**!

---

## Authors
Developed as part of a study on **Machine Learning models** for text classification.  
**Contributors:** HAFSA REDOUANE, SARAH SHAHIN 🚀  

---

