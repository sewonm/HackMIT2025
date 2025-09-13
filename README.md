# ArtMentor 🎨🤖

ArtMentor is an AI-powered art education tool that gives **constructive critique** and **practice exercises** for visual artworks.  
Upload your art → get structured feedback on composition, color, and contrast → receive practice suggestions → explore reference artworks.  

Built at **HackMIT 2025**.

---

## ✨ Features
- 🖼️ **Upload Artworks** — drag & drop your art for instant feedback  
- 🔍 **AI Critique** — structured review of composition, lighting, and technique  
- 📝 **Personalized Practice Exercises** — 3–step training tasks tailored to your weaknesses  
- 🖼️ **Reference Gallery** — historical & contemporary art examples for inspiration  
- 📈 **Progress Tracking** — upload iterations to see improvement over time  

---

## 🛠️ Tech Stack
- **Frontend**: React + Tailwind (polished, responsive UI)  
- **Backend**: Flask / Node.js (handles uploads & API calls)  
- **Models**:  
  - Hugging Face CV model (e.g. CLIP / ViT) for feature extraction  
  - Mentra + LLM for structured critique & practice generation  
- **Hosting**: Vercel (frontend), Render/Railway (backend)  

---

## 🚀 Quick Start

### Prerequisites
- Node.js + npm/yarn  
- Python 3.9+ (if using Flask backend)  
- Hugging Face + Mentra API keys

### Setup
```bash
# Clone repo
git clone https://github.com/<your-username>/HackMIT2025.git
cd artmentor

# Install frontend
cd frontend
npm install
npm run dev   # local dev server

# Install backend
cd ../backend
pip install -r requirements.txt
python app.py  # run server
