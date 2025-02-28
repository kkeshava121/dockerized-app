# dockerized-app
📌 Steps to Create and Add README.md
Run the following commands in your terminal:
cd /home/ubuntu/project-raw  # Navigate to your project folder


# Dockerized Frontend & Backend Application 🚀

This project contains a **simple frontend and backend application** running with Docker and Docker Compose.

## 📌 Project Structure
project-raw/ │── backend/ # Flask Backend │ ├── app.py │ ├── requirements.txt │ ├── Dockerfile │── frontend/ # Simple Nginx Frontend │ ├── index.html │ ├── Dockerfile │── docker-compose.yml # Docker Compose Configuration │── README.md # Project Documentation

---

## 🚀 **How to Run the Project**
### 1️⃣ **Clone the Repository**

git clone https://github.com/kkeshava121/dockerized-app.git
cd dockerized-app
2️⃣ Build and Start Containers
Run the following command to start the frontend and backend services:

docker-compose up -d --build
3️⃣ Verify Running Containers
docker ps
4️⃣ Test Backend API
curl http://localhost:5000/api
5️⃣ Test Frontend
Open your browser and visit:
http://localhost:3000
🔧 Backend (Flask)
The backend is a simple Python Flask application that exposes an API.

📌 Backend Files
app.py: Flask application.
requirements.txt: Dependencies.
Dockerfile: Docker configuration.
🚀 Run Backend Without Docker
cd backend
pip install -r requirements.txt
python app.py
🌐 Frontend (Nginx)
The frontend is a simple HTML page served using Nginx.

📌 Frontend Files
index.html: Simple UI page.
Dockerfile: Nginx configuration.
🐳 Docker Commands
Stop Containers

docker-compose down
Check Logs

docker-compose logs -f
Remove All Containers & Volumes

docker system prune -a
