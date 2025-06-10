# 🛡️ Phishing Website Detection using Machine Learning

This project presents a machine learning-based system to detect phishing websites based on their extracted features. The model classifies URLs as either legitimate or phishing, helping users avoid malicious sites.

## 📚 Project Overview

Phishing websites mimic trusted sites to steal sensitive user information such as usernames, passwords, and credit card numbers. Detecting these threats early is critical for maintaining cybersecurity. This project uses supervised learning models to distinguish phishing websites from safe ones based on feature analysis of the URLs and page content.

## 🧠 Features Used

The dataset includes 30+ features extracted from website URLs and HTML contents such as:

- Having IP Address
- URL Length
- Use of `@` Symbol
- Redirection in URL
- Prefix/Suffix in Domain
- HTTPS Token in Domain
- Anchor and Meta Tags
- Favicon Behavior
- DNS and WHOIS Features
- Request URLs and External Links

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Notebook**: Jupyter
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for ML models and evaluation
- **ML Models**:
  - Random Forest Classifier
  - Decision Tree
  - Logistic Regression
  - Support Vector Machine (SVM)

## 📊 Performance Metrics

Models are evaluated using:

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

## 📁 File Structure

Phishing_Website_Detection/
│
├── Phishing_Website_Detection.ipynb # Jupyter Notebook with full implementation
├── phishing_dataset.csv # Dataset (if available)
├── README.md # Project documentation


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/RohitPaulReddyG/phishing-website-detection.git
   cd phishing-website-detection

✅ Results
The best-performing model in the notebook achieved an accuracy of 95%, showing strong predictive power in identifying phishing URLs.

🧪 Future Work
Add deep learning models (e.g., LSTM for sequence-based detection).

Integrate live URL scanning and WHOIS lookups.

Deploy as a web API or browser extension.
