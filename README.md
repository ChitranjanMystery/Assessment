📜 Backend 
# Full Stack Greeting API - Backend

This is the backend for the Full Stack Developer Screening Task. It provides a simple API using **Node.js** and **Express.js** to return a personalized greeting.

## 🚀 Live Backend URL
https://assessment-2tln.onrender.com

## 🛠️ Installation & Setup

### 
**Clone the Repository**
git clone https://github.com/ChitranjanMystery/Assessment.git

cd your-backend-repo

**Install Dependencies**
npm install

**Run the Server**
node index.js
Or using nodemon:
npm install -g nodemon
nodemon index.js

🛠️ API Endpoints
GET /api/greet?name=YourName
✅ Success Response
json
{
  "message": "Hello, YourName! Welcome to Younglabs."
}
❌ Error Response (If name is missing)

json
{
  "error": "Name is required."
}

🌍 Deploy on Render
Push your code to GitHub.
Go to Render → New Web Service.
Connect your repository and deploy.
Set environment variables (PORT=5000) if needed.

🛠️ Tech Stack
Node.js + Express.js
CORS for handling cross-origin requests
Render for deployment

👨‍💻 Author
Chitranjan Thakur
https://github.com/ChitranjanMystery

📝 License
This project is licensed under the MIT License.
