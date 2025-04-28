# 🚨 Intrusion Detection System Using Machine Learning

An Intrusion Detection System (IDS) that leverages various Machine Learning algorithms to detect potential cyber threats effectively. This project uses algorithms like Decision Tree, Random Forest, Gradient Boosting, Naive Bayes, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) for training and evaluation.

---
## DATASET
 - KDD Cup 1999 dataset by DARPA
 - The whole dataset can be downloaded from- http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

## 📌 Table of Contents

- [Introduction](#introduction)
- [Architecture & Design](#architecture--design)
- [Algorithms Used](#algorithms-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## 🚀 Introduction

Intrusion Detection Systems are essential to cybersecurity. Using machine learning models, we can detect malicious activities by learning from historical data patterns. This project aims to build a reliable and scalable IDS that can classify network traffic as normal or malicious.

---

## 🏗️ Architecture & Design

- **System Design**: Defines modules like data collection, preprocessing, model training, and evaluation.
- **Data Flow**:
  - Input: Network traffic or intrusion dataset.
  - Preprocessing: Cleaning and feature extraction.
  - Model Training: Using ML algorithms.
  - Evaluation: Accuracy, Precision, Recall, F1 Score.
  - Output: Intrusion detected or not.

> **Class Diagram and Data Flow Diagrams** are available in the `docs/` folder.

---

## 🧠 Algorithms Used

- Decision Tree
- Gradient Boosting
- Random Forest
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

Each model is trained and evaluated separately to compare performance.

---

## 🎯 Evaluation Metrics

| Metric    | Description                                      |
|-----------|--------------------------------------------------|
| Accuracy  | Overall correctness of the model.               |
| Precision | How many predicted positives are actually true. |
| Recall    | How many actual positives were captured.        |
| F1 Score  | Harmonic mean of precision and recall.           |

---

## 🛠️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/btwshivam/Network-Intrusion-Detection.git
    cd Network-Intrusion-Detection
    ```
2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## 📈 Usage

- Prepare your dataset (e.g., NSL-KDD, CICIDS, or custom datasets).
- Update dataset paths inside the code if necessary.
- Run the model training:
    ```bash
    python train_models.py
    ```
- View evaluation metrics printed after training.

---

## 📊 Results

![test_accuracy_figure](https://github.com/user-attachments/assets/4528594a-b07c-4186-9223-1ab583320ddb)
![training_accuracy_figure](https://github.com/user-attachments/assets/78dd730f-779e-40d3-abca-53a7a3b866f5)
![train_time_figure](https://github.com/user-attachments/assets/a0fe7a4a-a372-48b1-9a98-12cd662d0511)
![test_time_figure](https://github.com/user-attachments/assets/efaedd77-002c-47bc-b4b2-cb711ebab54f)




## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

# 📢 Note
This project is intended for academic and learning purposes only.  
For production-grade IDS, deeper feature engineering, model optimization, and real-time handling are required.
