# 🛡️ BISync : AI-Powered BIS Compliance Assistant

![SIH](https://img.shields.io/badge/Smart_India_Hackathon-2026-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-MVP_Under_Development-blue?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Tech-FastAPI%20%7C%20Gemini%20%7C%20ChromaDB-success?style=for-the-badge)

**BISync** is a centralized, AI-driven compliance and verification platform designed for the Bureau of Indian Standards (BIS). It bridges the gap between consumers, manufacturers, and regulators by providing real-time, multilingual safety standard verifications using advanced Vision OCR and Vector-based Semantic Search.

---

## 🏆 Project Details
* **Hackathon:** Smart India Hackathon (SIH) 2026
* **Problem Statement ID:** SIH26107
* **Theme:** Smart Automation
* **Category:** Software
* **Team Name:** CodeX99

---

## 🚀 Key Features

### 1. 👥 For Consumers (B2C)
* **Instant Scanner:** Capture a product label or ISI mark via live camera or image upload.
* **Smart Explanation Engine:** Translates complex IS codes into simple, understandable safety insights.
* **Multilingual Support:** Delivers compliance results in regional languages via the **Bhashini API**.

### 2. 🏭 For Industries & Manufacturers (B2B)
* **Pre-Market Audit:** Manufacturers can run automated checks on product specs before official BIS submission.
* **Instant Reporting:** Generates downloadable, bias-free compliance reports.

### 3. 🏛️ For Regulators (B2G)
* **Centralized Dashboard:** Real-time tracking of nationwide product compliance.
* **Fraud Detection:** Flags counterfeit ISI marks and automated alert generation for non-compliant batches.

---

## 🛠️ Technology Stack

* **Frontend & UI:** HTML5, CSS3, Bootstrap 5, JavaScript (Accelerated by v0.dev/Bolt.new)
* **Backend Engine:** Python, FastAPI
* **AI & Intelligence:** 
  * **Google Gemini Vision API:** For high-accuracy OCR and visual feature extraction.
  * **Bhashini API:** For seamless regional language translation.
* **Database & Search:**
  * **ChromaDB:** Vector database for lightning-fast semantic retrieval of BIS rules.
  * **MySQL:** Relational database for user roles and logging.
* **Deployment & Version Control:** GitHub, Vercel, Render.

---

## 📂 Core Product Categories Indexed (MVP Scope)
Our Vector Database currently indexes safety parameters and compliance rules for 15 high-impact commercial products:
1. Smartphones & Mobile Handsets
2. Mobile Phone Chargers & Adapters
3. LED Bulbs & Home Lighting
4. Children's Plastic & Electronic Toys
5. Electric Irons & Small Kitchen Appliances
6. Packaged Drinking Water Bottles
7. Two-Wheeler Helmets
8. Domestic Pressure Cookers
9. Electric Ceiling Fans
10. Switches, Sockets & Plug Tops
11. Electric Water Heaters / Geysers
12. Plastic Water Storage Tanks
13. Miniature Circuit Breakers (MCBs)
14. Domestic LPG Stoves & Gas Appliances
15. TMT Steel Bars & Cement for Construction

---

## ⚙️ Architecture & Workflow
1. **User Input:** Image/Text query is uploaded via the frontend.
2. **AI Extraction:** Gemini API parses the text, IS codes, and visual data (Phase 1).
3. **Semantic Matching:** The extracted data is queried against local BIS standards stored in ChromaDB (Phase 2).
4. **Validation & Output:** The FastAPI backend formulates a Pass/Fail report with explanations and translates it via Bhashini before displaying it to the user.

---

## 💻 Local Setup & Installation (Developer Guide)

**1. Clone the Repository:**
```bash
git clone [https://github.com/your-username/BISync.git](https://github.com/your-username/BISync.git)
cd BISync
