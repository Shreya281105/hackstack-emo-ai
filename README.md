
 🩺 EmoCare Centre – Medicine Suggestion & Disease Prediction System

**EmoCare Centre** is an intelligent healthcare web assistant built using **Flask**, designed to predict diseases from user-input symptoms and recommend relevant treatments. It offers medications, precautions, diet plans, and workout suggestions — making basic healthcare more accessible using machine learning.

---

## 🚀 Features

- ✅ **Disease Prediction** from symptoms using an **SVC (Support Vector Classifier)** model
- 💊 **Medicine Recommendations** based on predicted disease
- ⚠️ **Precaution Guidelines** to prevent worsening conditions
- 🥗 **Personalized Diet Suggestions**
- 🏃 **Workout Plans** aligned with the illness
- 🧠 Optional **EmoCare Therapy Chatbot** module for emotional support
- 🎤 **Voice Input** support for symptoms using speech recognition
- 🔍 **Dynamic, Autocomplete Symptom Selector** with multi-input support
- 🧪 **Synthetic Data Integration** to improve prediction accuracy

---

## 🧠 How It Works

1. User inputs symptoms (text or voice).
2. The trained ML model predicts the disease.
3. Based on prediction, the app displays:
   - Disease Description
   - Recommended Medicines
   - Precautions
   - Diet Suggestions
   - Workouts
4. (Optional) An emotional support chatbot can be integrated.

---

## 🗃️ Project Structure

```
EmoCare-Centre/
│
├── main.py                      # Flask app
├── medicinerecommender.py       # Logic for medicine, diet, and workouts
├── dataset/                     # CSV files for predictions and suggestions
│   ├── disease_dataset.csv
│   ├── medication_data.csv
│   ├── precautions.csv
│   ├── diet.csv
│   ├── workout.csv
│   └── synthetic_symptom_data.csv
│
├── templates/                   # HTML templates
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── blog.html
│
├── static/                      # CSS and assets
│   └── style.css
│
└── model/                       # Machine learning model
    └── svc_model.pkl
```

---

## 🛠️ Tech Stack

- **Python 3**
- **Flask**
- **Scikit-learn**
- **Pandas / NumPy**
- **HTML5 / CSS3 / JavaScript**
- **Bootstrap** for UI styling

---

## ⚙️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/EmoCare-Centre.git
   cd EmoCare-Centre
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   python main.py
   ```

4. Open in browser:
   ```
   http://127.0.0.1:5000/
   ```

---

## 📈 Future Enhancements

- 🔗 API-based symptom validation
- 📷 Image-based disease prediction
- 🤖 Full integration of **EmoCare** chatbot module
- 📲 Mobile-first UI with PWA capabilities
- 🔐 Login/Register functionality for user personalization

---

## 📸 Screenshots

![WhatsApp Image 2025-04-12 at 08 17 29_39c3a22b](https://github.com/user-attachments/assets/bfc92319-9712-4b9b-ae69-929899189d39)
![WhatsApp Image 2025-04-12 at 08 19 23_11b9e500](https://github.com/user-attachments/assets/3b4fc1d4-281c-4d94-8add-fafef3072924)
![WhatsApp Image 2025-04-12 at 08 19 45_7c5ea255](https://github.com/user-attachments/assets/a5086588-c59e-4364-9622-ee0115796df2)
![WhatsApp Image 2025-04-12 at 08 20 22_6e705a5d](https://github.com/user-attachments/assets/5ad81a2e-3113-4705-943c-f2fa2d651c11)
![image](https://github.com/user-attachments/assets/e7f7093a-b6e0-4e12-ae02-20cdac9ac389)

CHATBOT for emotional support


![WhatsApp Image 2025-04-11 at 20 57 36_63663817](https://github.com/user-attachments/assets/68381cdd-a411-42f4-afc1-f194f54eb6f1)
![WhatsApp Image 2025-04-11 at 20 57 48_30c2af82](https://github.com/user-attachments/assets/aaab966d-ec07-49ba-aa7e-219a461aadc5)


Predicition through image

![WhatsApp Image 2025-04-11 at 18 48 00_93ba7fcd](https://github.com/user-attachments/assets/c352a2af-a85e-45c3-bef4-44c46a09ae08)


