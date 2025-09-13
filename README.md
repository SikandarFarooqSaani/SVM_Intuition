### 🧠 Support Vector Machine (SVM) — Intuition & Visualization
### 📌 Project Overview

This project explores the intuition behind Support Vector Machines (SVMs) using a dummy dataset.
We walk through linear separability, margin maximization, support vectors, and the effect of soft margins (C parameter) with clear visualizations.

### ⚙️ Tools & Libraries

NumPy

SciPy

Matplotlib

###🔎 Steps & Findings

### 1. Creating a Dummy Dataset

Generated a linearly separable dataset.

<img width="538" height="417" alt="sv1" src="https://github.com/user-attachments/assets/4bcbfa81-7c3d-421f-b771-8a818bf289ac" />


### 2. Linear SVM Classifier

Trained an SVC with kernel = linear.

Plotted the separating hyperplane with margins.

<img width="538" height="417" alt="sv2" src="https://github.com/user-attachments/assets/51408a27-f088-4439-bab7-de0f339a1686" />


### 3. Support Vectors

Added more data points.

Visualization shows multiple points lying on the margin → these are the support vectors.
<img width="1480" height="532" alt="sv3" src="https://github.com/user-attachments/assets/afef14f5-9462-47d9-bdce-91b3d2b29e3d" />

Key takeaway: Only support vectors define the decision boundary, not all data points.

### 4. Soft Margin SVM (C parameter effect)

Created another dataset that is almost linearly separable (some overlap).
<img width="551" height="417" alt="sv4" src="https://github.com/user-attachments/assets/ee91ec70-1c89-4c15-aa7f-f3f80f371488" />


Explored how the C parameter controls the margin:

High C (large penalty) → narrow margin, few misclassifications (overfitting risk).

Low C (small penalty) → wider margin, more misclassifications allowed (underfitting risk).

<img width="1475" height="533" alt="sv5" src="https://github.com/user-attachments/assets/71e2552d-49d7-4a5c-80ab-afa0123ea294" />


### 📊 Key Intuitions Learned

SVM finds a hyperplane that maximizes the margin between classes.

Support vectors are the critical points that determine the boundary.

The C parameter balances between margin width and classification errors (soft margin SVM).

✨ This mini-project built intuition for how SVM works, both in perfect separability and in real-world noisy data cases.
