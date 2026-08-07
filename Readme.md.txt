# 🛡️ Cyber Guardian AI

### AI-Powered Cybersecurity Assistant

Cyber Guardian AI is a lightweight cybersecurity application that helps users identify common digital security risks through phishing email detection, suspicious URL analysis, and password strength checking.

## 🚀 Features

* 📧 **Phishing Email Detector** — Detects common phishing indicators in email messages.
* 🔗 **URL Risk Checker** — Analyzes URLs for suspicious characteristics.
* 🔐 **Password Strength Checker** — Evaluates basic password security characteristics.
* 📊 **Security Reports** — Provides risk scores, threat levels, findings, and recommendations.

## 🛠️ Technologies Used

* Python
* Scikit-learn
* Pandas
* Gradio
* Regular Expressions
* Google Colab

## 🧠 AI Methodology

The phishing email detector uses **TF-IDF Vectorization** and **Logistic Regression**.

The URL and password modules use lightweight rule-based analysis to identify common security risks.

## ⚙️ Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

```bash
python app.py
```

The Gradio application will provide a web interface that can be opened in a browser.

## 🔍 Project Modules

### 📧 Email Scanner

Analyzes email content for suspicious keywords and common phishing patterns.

### 🔗 URL Scanner

Checks URLs for characteristics such as:

* HTTP instead of HTTPS
* IP addresses
* Unusually long URLs
* Suspicious keywords
* Multiple subdomains
* Suspicious URL symbols

### 🔐 Password Checker

Checks basic password characteristics including:

* Password length
* Uppercase letters
* Lowercase letters
* Numbers
* Special characters

## 📊 Output

The application provides:

* Risk score
* Threat level
* Detected security indicators
* Security recommendations

## 🔮 Future Enhancements

* Larger phishing datasets
* Advanced machine-learning models
* Real-time threat intelligence
* Domain reputation analysis
* Malware detection
* Browser extension integration
* Real-time security monitoring

## ⚠️ Disclaimer

Cyber Guardian AI is an educational cybersecurity prototype. It uses simplified machine-learning and rule-based techniques and should not be considered a replacement for professional cybersecurity or threat-intelligence software.

## 👩‍💻 Author

**Kruthikashree**

---

### 🛡️ Cyber Guardian AI

**Detect • Analyze • Protect**
