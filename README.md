🧠 IDS-ML: Intrusion Detection System using Machine Learning
🚀 Real-time Network Intrusion Detection Dashboard

IDS-ML is a real-time Intrusion Detection System built using FastAPI (backend) and React + Vite (frontend).
It detects and visualizes live cyber threats using Machine Learning (XGBoost) and WebSocket live updates.

⚙️ How to Run the Project
🪶 Step 1 — Clone and Open

Clone this repository and open it in VS Code.

🌐 Step 2 — Change Your IP

Open the .env file and replace the IP with your local IP address:

VITE_API_BASE=http://YOUR_IP:8000
VITE_WS_URL=ws://YOUR_IP:8000/ws/stream


Example: 192.168.1.37 → change this part only.

💻 Step 3 — Run Frontend

In the terminal, run:

npm install
npm run dev


Your frontend will start at:
👉 http://localhost:8080 or http://YOUR_IP:8080

⚙️ Step 4 — Run Backend

Click the ➕ (plus) icon on the terminal tab to open a new terminal, then run:

cd backend
uvicorn main:app --reload --host 0.0.0.0 --port 8000


Your backend runs at:
👉 http://YOUR_IP:8000
WebSocket stream:
👉 ws://YOUR_IP:8000/ws/stream

✅ Step 5 — Open in Browser

Now open:
👉 http://YOUR_IP:8080

You’ll see:

📊 Real-time dashboard updates

🧠 Live intrusion detections

⚡ Analysis with charts and metrics

🧠 Tech Stack

Frontend: React + TypeScript + Vite + TailwindCSS + Recharts

Backend: FastAPI + Python + XGBoost

Database: Supabase

👥 Team Members:

Prakhar Singh
Samkit Jain
Ashish Chouhan
Gaurav Singh
Tarun Dev Taliyan

🏆 HackVerse 1.0 Project

Real-time ML-powered intrusion detection and visualization system for modern network security.

📜 License

MIT License © 2025 — THE HACKER'S
