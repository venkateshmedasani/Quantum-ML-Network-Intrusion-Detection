# Quantum-ML-Network-Intrusion-Detection
Quantum Machine Learning project applying a Quantum Support Vector Classifier (QSVC) with Qiskit to detect network intrusions using the NSL-KDD dataset. Achieved 93% accuracy and 0.98 AUC, demonstrating the feasibility of quantum-enhanced intrusion detection systems.

This project explores the use of **Quantum Machine Learning (QML)** for detecting network intrusions, leveraging a **Quantum Support Vector Classifier (QSVC)** with Qiskit. The model is evaluated against classical machine learning methods to benchmark feasibility, performance, and scalability in real-world intrusion detection systems.  

## 📌 Features
- Implements **Pegasos QSVC** with Qiskit’s quantum kernel.
- Feature selection reducing input dimensionality by **75%+**.
- Evaluation in a **1,024-dimensional quantum feature space**.
- Handles noisy quantum hardware challenges with **batch-wise evaluation**.
- Performance compared with top-performing **classical ML models**.

## 📊 Results
The QSVC-based approach achieved **93% accuracy** and an **AUC of 0.98**, matching classical ML benchmarks while leveraging quantum feature mappings.  

| Model              | Accuracy | AUC  |
|--------------------|----------|------|
| Quantum SVC (QSVC) | 94%      | 0.98 |
| Classical SVM      | 92%      | 0.98 |

## Visualizations
**Batch wise accuracy and F1 score**


<img width="790" height="390" alt="image" src="https://github.com/user-attachments/assets/bee6807e-c59b-4e58-82a9-12cd98e84523" />



**Confusion Matrix**


<img width="556" height="455" alt="image" src="https://github.com/user-attachments/assets/27d9cca3-40ab-4246-bd80-8643a3c0a917" /> 



**ROC Curve**


<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/c5432a81-9482-4666-83f4-6f23e335b413" />



**Model Comparison**


<img width="772" height="566" alt="image" src="https://github.com/user-attachments/assets/3a921511-add6-49fb-82f6-6884d988fa5a" />


These results demonstrate that quantum-enhanced models can achieve strong predictive performance while opening pathways toward **scalable, hardware-ready intrusion detection systems**.  

## ⚙️ Installation
Clone this repository:
```bash
git clone https://github.com/<your-username>/quantum-intrusion-detection.git
cd quantum-intrusion-detection




