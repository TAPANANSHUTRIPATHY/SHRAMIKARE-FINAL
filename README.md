# 📌 ShramiKare – Multilingual Digital Health Record System  

![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)  
![Made with React](https://img.shields.io/badge/Frontend-React.js-61DAFB?logo=react&logoColor=white&style=flat-square)  
![Made with FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)  
![Database](https://img.shields.io/badge/Database-Firebase-F6820D?logo=firebase&logoColor=white&style=flat-square)  
![Hackathon](https://img.shields.io/badge/Event-SIH%202025-orange?style=flat-square)  

---

## 🌟 Overview  
**ShramiKare** is a **Digital Health Record Management System** designed for **migrant workers in Kerala**, aligned with **SDG-3 (Good Health and Well-being)**.  

The platform ensures **portable, multilingual, and paperless medical records**, accessible via **QR codes, Aadhaar lookup, or SMS-based reminders**, empowering migrant workers with seamless healthcare access.  

---

## 🖼️ Screenshots & Demo  

👉 Replace these placeholders with actual screenshots or demo GIFs.  

### 🔹 Landing Page  
![Screenshot_19-9-2025_232943_localhost](https://github.com/user-attachments/assets/76b4b9a2-26f1-473e-bc46-21cab272abc9)

### 🔹 OTP Login Page
![Screenshot_19-9-2025_231553_localhost](https://github.com/user-attachments/assets/54d97b81-f437-4eeb-a89f-93786faae95d)

### 🔹 Sample OTP SMS
![a4843620-0cf0-462f-bdad-120fbafd44de](https://github.com/user-attachments/assets/1c1d6db2-af59-4c33-9251-91498bfb6bd2)


### 🔹 Facility Details Page
![Screenshot_19-9-2025_23165_localhost](https://github.com/user-attachments/assets/83ffd4bd-2d76-47b6-81fd-3ac0e768322d)

### 🔹 Aadhaar Lookup
![Screenshot_19-9-2025_231613_localhost](https://github.com/user-attachments/assets/90f8259a-44e4-4097-9d2a-f28f3ed273ce)

### 🔹 Health Records Dashboard  
![Screenshot_19-9-2025_231622_localhost](https://github.com/user-attachments/assets/b32f0768-d4d3-4a62-bfe0-0b6d0e1ad9d8)

### 🔹 QR Scan Result
<img width="780" height="972" alt="Screenshot 2025-09-19 223850" src="https://github.com/user-attachments/assets/63682fbf-7642-4ed5-b2f3-1edecad35f8b" />


### 🔹 SMS Reminder Workflow  
<img width="951" height="809" alt="Screenshot 2025-09-19 224358" src="https://github.com/user-attachments/assets/bde0d5de-2413-4136-b886-f88daba12a2d" />

### 🔹 Sample SMS Reminder
![3f6a33eb-1f2a-4d25-adf0-95bd88a55e31](https://github.com/user-attachments/assets/09c93a76-2073-4f0c-872f-641992c15669)
![0642aee5-556d-4b77-a995-b7c469403825](https://github.com/user-attachments/assets/8ba0e65d-111a-4ae2-8c23-2a2ce74b2200)


### 🔹 Outbreak Prediction Workflow 
<img width="800" height="976" alt="Screenshot 2025-09-19 224315" src="https://github.com/user-attachments/assets/78ecab65-bf6d-4f6a-a4ac-2d2afc387aa9" />


---

## 🩺 Problem Statement  
- Migrant workers often lack **consistent health records** across states.  
- Paper-based systems are **prone to loss, duplication, and delays**.  
- **Language barriers** prevent workers from understanding health instructions.  
- Limited access to **feature phones & low connectivity** challenges inclusivity.  

---

## 💡 Our Solution  
- **Multilingual Mobile App** (Malayalam, Odia, Bengali, Assamese, Hindi).  
- **QR Code + Aadhaar Lookup** for instant access to health records.  
- **Offline-first caching** with sync on reconnection.  
- **Automated SMS reminders** for vaccinations, check-ups, and follow-ups.  
- **Secure cloud backend** for real-time health data availability.  
- **Analytics dashboard** for policymakers and NGOs.  

---

## 🔧 Tech Stack  

| Layer       | Technology |
|-------------|------------|
| **Frontend** | ⚛️ React.js, Tailwind CSS |
| **Backend**  | 🐍 FastAPI (Python) |
| **Database** | 🔥 Firebase Firestore |
| **Messaging** | 📩 Twilio SMS API |
| **Identity** | 🆔 Aadhaar |

---

## ⚙️ System Architecture  

```mermaid
flowchart TD
  User[👨‍🔧 Migrant Worker] -->|QR / Aadhaar| App[📱 Shramikare App]
  App -->|API Calls| Backend[☁️ FastAPI + Firebase]
  Backend --> DB[(🗄️ Firestore DB)]
  Backend --> Twilio[✉️ Twilio SMS API]
  DB --> Analytics[📊 Analytics & Dashboards]
  Analytics --> NGO[🏥 Policymakers/NGOs]
```

---

## 🚀 Features

* ✅ **Portable Records** → Access anywhere via Aadhaar or QR
* ✅ **Multilingual UX** → Supports 5+ regional languages
* ✅ **Inclusive** → Works on smartphones + feature phones
* ✅ **Offline-first** → Sync when network is back
* ✅ **Smart Alerts** → Automated SMS for due checkups
* ✅ **Analytics Dashboard** → Track outbreaks & public health

---

## 🔐 Security & Privacy

* Aadhaar integration with **user consent**.
* Role-based access for doctors, NGOs, and workers.
* Encrypted records stored in **Firestore**.
* Compliance with **Digital India Health Mission guidelines**.

---

## 📈 Impact & Benefits

* **Migrant Workers** → Portable, accessible, and understandable records.
* **Healthcare Staff** → Quick record lookup → faster treatment.
* **Government/NGOs** → Real-time data-driven insights.
* **Society** → Supports **Digital India, Atmanirbhar Bharat, Swachh Bharat**.

---

## 🛠️ Installation & Setup

```bash
# Clone the repo
git clone https://github.com/TAPANANSHUTRIPATHY/ShramikareGreenHealth.git
cd ShramikareGreenHealth

# Install dependencies
npm install

# Run development server
npm run dev
```

Backend setup (FastAPI + Firebase):

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 📚 References

* [SIH 2025 Problem Statement](https://sih.gov.in/sih2025PS)
* [Firebase Firestore Docs](https://firebase.google.com/docs/firestore)
* [Twilio SMS API](https://www.twilio.com/docs/sms)
* [Gemini API](https://ai.google.dev/gemini-api/docs)
* [Googletrans](https://pypi.org/project/googletrans/)

---

## 👥 Team – **StellaRythm**

* **Tapananshu Tripathy**
* **Ujjwal Singh**
* **Shubham Kumar**
* **Hritika Shankhdhar**
* **Palak Singh**
* **Tejas Mahapatra**

---
