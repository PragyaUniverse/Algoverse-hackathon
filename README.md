# 🌍 **Algoverse Hackathon**
Personal Carbon Footprint Tracker
# 🔥 LowkeyCarbon
### Chill habits, low carbon.

A smart, gamified carbon tracking web app that helps users visualize and reduce their daily emissions through simple actions.

---
## 📌 Table of Contents

- [🌍 About](#-about)
- [✨ Features](#-features)
- [🧠 How We Calculate Emissions](#-how-we-calculate-emissions)
- [🧰 Tech Stack](#-tech-stack)
- [🚀 Getting Started](#-getting-started)

## 📖 ABOUT
The Problem: Carbon is Invisible
 Despite rising climate awareness, most individuals don’t realize how their daily choices affect the planet — especially in
 India, where personal carbon tracking tools are scarce.
 - 🔍 Lack of Awareness: Less than 15% know their own carbon footprint
 - 🌆 Hidden Emissions: Urban individuals emit over 500 kg CO₂/month without realizing it
 - 🛒 Everyday Drivers: AC usage, Zomato orders, Flipkart shopping — all contribute
 - 📉 No Clear Feedback: People can't change what they can't measure

**LowkeyCarbon** solves this with a simple, interactive platform that tracks your carbon footprint and helps reduce it through **smart inputs, visual feedback**, and **gamified learning**.

---

## ✨ FEATURES

- ✍️ **Input Tracker** – Log daily travel, food, electricity use  
- 📸 **Receipt Scanner** – Scan Zomato, Flipkart, etc., and auto-calculate CO₂ (Launching Soon!)
- 📊 **CO₂ Dashboard** – Visualize emissions over time  
- 🏆 **Gamification** – Earn eco-habit badges & streaks (Launching Soon!)
- 🤖 **Eco-Bot** – Chatbot tips & interactive tracking (Launching Soon!) 
- 📚 **Story Mode** – Learn sustainability via interactive storytelling (Launching Soon!)

---

## 🧠 HOW WE CALCULATE EMISSIONS

- Activities and purchases are mapped to specific CO₂ emission
  factors
- Results are aggregated and visualized daily, weekly, and monthly
  on user dashboards
- Data collected via manual inputs (travel, food) and receipt OCR
  (Zomato, Flipkart)
 - Uses verified sources:
  • India GHG Program
  • IPCC
  • UK DEFRA

---

## 🧱 TECH STACK

| 🔧 Component        | 💻 Tech Stack                              |
|--------------------|--------------------------------------------|
| **Frontend UI**     | HTML, CSS, JavaScript                      |
| **Backend API**     | Python (Flask)                             |
| **Database**        | Firebase / MongoDB                         |
| **OCR Engine**      | Tesseract.js / Google Vision API           |
| **Emission Engine** | Custom logic + Emission factor databases   |
| **Chatbot**         | Python + ML (LLM-based)                    |

---
## 🚀 Getting Started

### For Users:

> 👉 Just open [https://lowkeycarbon.app](https://lowkeycarbon.app) in your browser.  
> No install needed!

### For Developers:

```bash
# Clone the repository
git clone https://github.com/yourusername/lowkeycarbon.git
cd lowkeycarbon

# Install dependencies
pip install -r requirements.txt
npm install

# Run backend
flask run

# Open frontend (if separate)
npm start




