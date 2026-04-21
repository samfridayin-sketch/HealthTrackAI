# Contributing to HealthTrack AI 🤝

Thank you for your interest in contributing to HealthTrack AI! We welcome contributions from everyone.

---

## 📋 Code of Conduct

Be respectful, inclusive, and professional. Treat all contributors with kindness.

---

## 🚀 Getting Started

### 1. Fork the Repository
```bash
# Click the "Fork" button on GitHub
git clone https://github.com/YOUR-USERNAME/HealthTrack-AI.git
cd HealthTrack-AI
git remote add upstream https://github.com/samfridayin-sketch/HealthTrack-AI.git
git checkout -b feature/your-feature-name
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
pip install pytest black flake8  # Dev tools
cd frontend
npm install
npm start
docker-compose up -d
git commit -m "feat: Add new feature"
git commit -m "fix: Fix bug"
git commit -m "docs: Update documentation"
# Backend
pytest tests/ -v

# Frontend
npm test
👉 **Create this simplified version instead, then reply "Done 8" for File 9!**
