# 🧠 AIsecTest Insight — MongoDB Challenge

**AIsecTest Insight** is an intelligent analysis and visualization platform for cybersecurity data. It is an adaptation of the AIsecTest system focused on the MongoDB Challenge at the [AI in Action Hackathon](https://ai-in-action.devpost.com/).

The project leverages **MongoDB Atlas**, **vector search**, **FastAPI**, **React**, and **AI-driven NLP** to enable semantic search and smart exploration of incidents and vulnerabilities.

---

## 🚀 Key Features

- 🔍 Semantic search of security incidents (NLP + Vector Search)
- 📊 Visualization of threat trends
- ⚠️ Identification and classification of vulnerabilities
- 🔗 Integration with MongoDB Atlas and AI services

---

## 🧱 Project Structure

aisectest-insight-mongodb/
├── backend/ # FastAPI backend with vector search
├── frontend/ # React user interface
├── data/ # Sample data
├── deploy/ # Deployment instructions (Render, Vercel)
├── .env.example # Environment configuration template
├── docker-compose.yml # Container orchestration
└── README.md # Project documentation

---


---

## 💡 Inspiration

This project builds upon the original **AIsecTest** platform, which was designed to evaluate self-awareness in AI systems. AIsecTest Insight expands this vision by exploring external data — such as security incidents and vulnerability reports — with semantic intelligence and search capabilities.

---

## 🧰 Tech Stack

| Technology           | Description                                |
|----------------------|--------------------------------------------|
| MongoDB Atlas        | Document store and vector search engine    |
| FastAPI              | Lightweight Python backend framework       |
| Sentence Transformers| NLP embedding model for semantic search    |
| React + Tailwind     | Frontend UI framework                      |
| Docker               | Containerization for backend and frontend  |

---

## ⚙️ Getting Started (Local)

1. Clone the repository
   
3. Create a `.env` file from the template:
   ```bash
   cp .env.example .env

3.Update MONGODB_URI with your Atlas connection string

4. Run locally:

docker-compose up --build

Backend: http://localhost:8000

Frontend: http://localhost:3000
