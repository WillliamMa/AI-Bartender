
# 🍸 BarBuddy

[![Web App CI](https://github.com/software-students-spring2025/5-final-machine-not-learning/actions/workflows/webci.yml/badge.svg)](https://github.com/software-students-spring2025/5-final-machine-not-learning/actions/workflows/webci.yml)

BarBuddy is your personal cocktail companion. It helps users manage their home bar inventory, receive cocktail suggestions based on available ingredients, track expiring items, and save favorite recipes. Whether you're a seasoned mixologist or just getting started, BarBuddy makes it easy to explore and enjoy cocktails at home.

---

## 📦 Docker Images
- [Web Application](https://hub.docker.com/repository/docker/williamma205/webapp/general)

---

## 👥 Team Members

- [Xiaowei Ma](https://github.com/maxiaowei)
- [Mandy Mao](https://github.com/WillliamMa)
- [Rishi Rana](https://github.com/Rishi-Rana1)
- [Max Luetke Meyring](https://github.com/maxlmeyring)

---

## Digital Ocean Deployed URL

You can access the application from:

https://bartender-6r98j.ondigitalocean.app

## 🛠️ Setup Instructions

### Prerequisites

- Docker & Docker Compose
- Python 3.10
- MongoDB Atlas account

### 1. Clone the repo

```bash
git clone https://github.com/software-students-spring2025/5-final-machine-not-learning.git
```

### 2. Environment Setup

Enter the project repository:

```bash
touch .env
```

Edit `.env` and set the following:

```
MONGO_URI=mongodb+srv://youruser:yourpass@yourcluster.mongodb.net/?retryWrites=true&w=majority
OPENAI_API_KEY=your-openai-api-key
SECRET_KEY=your-secret-key
```

### 3. Run with Docker

```bash
docker-compose up --build
```

App will be available at `http://127.0.0.1:8080`

---


