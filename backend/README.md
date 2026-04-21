# HealthTrack AI 🏥💚

**AI-powered chatbot for weight loss tracking and personalized nutrition guidance**

An intelligent conversational assistant that helps users track their weight loss journey, log meals, and receive personalized nutrition recommendations powered by OpenAI's GPT models.

---

## 🎯 Features

- 🤖 **AI Chatbot Interface** - Natural language conversation for meal logging and nutrition advice
- 📊 **Weight Tracking** - Track weight progress over time with visual analytics
- 🍽️ **Meal Logging** - Easy-to-use interface for logging meals and calories
- 💡 **Personalized Recommendations** - Get nutrition and fitness tips based on your profile
- 📈 **Progress Analytics** - View detailed charts and statistics about your health journey
- 🔐 **Secure Authentication** - JWT-based user authentication and data privacy
- 🗄️ **PostgreSQL Database** - Robust data storage and management
- 🐳 **Docker Support** - Easy deployment with Docker and Docker Compose

---

## 🛠️ Tech Stack

### Backend
- **FastAPI** - Modern Python web framework
- **LangChain** - Framework for building AI applications
- **OpenAI API** - GPT models for intelligent chatbot
- **PostgreSQL** - Relational database
- **SQLAlchemy** - ORM for database management
- **Uvicorn** - ASGI server

### Frontend
- **React 18** - UI library
- **TypeScript** - Type-safe JavaScript
- **Axios** - HTTP client
- **Tailwind CSS** - Styling framework

### DevOps
- **Docker** - Containerization
- **Docker Compose** - Multi-container orchestration
- **GitHub Actions** - CI/CD automation

---

## 📋 Prerequisites

Before you begin, ensure you have:
- Python 3.11+
- Node.js 18+
- Docker & Docker Compose
- OpenAI API Key
- PostgreSQL (if running locally without Docker)

---

## 🚀 Quick Start

### Option 1: Using Docker Compose (Recommended)

```bash
# Clone the repository
git clone https://github.com/samfridayin-sketch/HealthTrack-AI.git
cd HealthTrack-AI

# Copy environment variables
cp .env.example .env

# Edit .env and add your OpenAI API Key
nano .env

# Start all services
docker-compose up -d

# Access the application
# Frontend: http://localhost:3000
# Backend API: http://localhost:8000
# API Docs: http://localhost:8000/docs
