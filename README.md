# NutriAI - AI Nutrition Coach & Metabolic Food Companion 🥗⚡

NutriAI is a clinical-grade, ultra-responsive AI food recognition scanner and metabolic health companion powered by Google Gemini Vision.

---

## 🌟 Key Features

- 📸 **Multimodal Food Scanner:** Instant dish identification, portion estimation, and macro/micronutrient breakdown.
- ⚡ **Zero-Lag Interface:** Hardware-accelerated animations, debounced inputs, and lightweight modern CSS design.
- 🩺 **Metabolic Health Profiling:** Personalized calorie, macro, and fiber targets tailored for Diabetes, PCOS, Hypertension, Thyroid, and Weight Goals.
- 🤖 **Interactive AI Coach:** Real-time conversational nutrition coach with personalized meal plans and guidance.
- 💧 **Smart Vitals & Hydration Log:** Daily water tracker and clinical biomarkers logger.

---

## 🚀 Quick Start (Local Setup)

### 1. Clone or Download the Repository
```bash
git clone https://github.com/your-username/nutriai.git
cd nutriai
```

### 2. Set Up Virtual Environment
```bash
# Windows
python -m venv .venv
.\.venv\Scripts\activate

# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables
Create a `.env` file in the root directory:
```env
GEMINI_API_KEY=your_gemini_api_key_here
PORT=8000
```

### 5. Start the Server
```bash
python server.py
```
Open **`http://localhost:8000`** in your browser.

---

## 🌐 Deploy to Cloud (Free Public URL)

To make your website accessible to anyone worldwide, deploy to **[Render.com](https://render.com/)**:

1. Create a free account on **Render.com** and connect your GitHub account.
2. Click **New +** > **Web Service** and choose this repository.
3. Configure:
   - **Runtime:** `Python 3`
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `python server.py`
4. In **Environment Variables**, add:
   - Key: `GEMINI_API_KEY`
   - Value: `Your Gemini API Key`
5. Click **Deploy Web Service** to get your public `https://your-app.onrender.com` link!
