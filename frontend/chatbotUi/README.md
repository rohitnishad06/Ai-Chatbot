# AI-Based Chatbot

This project is an AI-powered chatbot that uses **Natural Language Processing (NLP)** and **Machine Learning (ML)** to understand user queries and respond appropriately in real-time. It is built with a **React.js frontend**, **FastAPI backend**, and trained using Python-based ML models.

---

## Problem Statement

In the digital age, users expect instant and intelligent responses from systems. Manual support is often slow, inconsistent, and resource-intensive. An AI-based chatbot provides a scalable solution by offering 24/7 conversational support using machine learning and NLP.

---

## Features

- Intent recognition using ML classifier (Naive Bayes / Logistic Regression)
- Predefined responses for common queries
- Seamless frontend-backend integration
- Real-time chat interface using React
- Fast and lightweight backend using FastAPI

---

## Tech Stack

| Layer       | Technology        |
|-------------|-------------------|
| Frontend    | React.js          |
| Backend     | FastAPI (Python)  | 
| Env. Mgmt   | Conda             |
| Styling     | Tailwind CSS      |

---

## 🚀 How to Run the Project

### 🔹 Prerequisites
- Node.js & npm
- Python 3.8+ with Conda
- Git

### 🔹 Backend (FastAPI)

```bash
# Clone the repo
git clone https://github.com/rohitnishad06/Ai-Chatbot.git
cd ai-chatbot/backend

# Create conda environment
conda create -n chatbot python=3.8
conda activate chatbot

# Install dependencies
pip install -r requirements.txt

# Run the FastAPI app
uvicorn app:app --reload


cd ../frontend

# Install dependencies
npm install

# Start the React app
npm run dev 
