7-Agent Decision Autopsy

An AI-powered decision analysis system that simulates 7 expert agents to break down complex decisions and provide structured insights.

🚀 Features
    Problem understanding 
    Clarification of assumptions
    Deep analysis
    Risk evaluation
    Predictions
    Strategy suggestions
    Final actionable advice
     
🛠 Tech Stack
   Frontend: React (Vite)
   Backend: FastAPI
   LLM API: Groq (LLaMA / Mixtral)
   Language: Python + JavaScript
   
📂 Project Structure
backend/      → FastAPI server
frontend/     → React UI

⚙️ Setup Instructions

1️⃣ Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

Create .env file:
GROQ_API_KEY=your_api_key_here

2️⃣ Frontend
cd frontend/multiagent
npm install
npm run dev

🌐 Usage
Enter a decision problem
Click Analyze
Get structured insights from 7 AI agents

📸 Demo
<img width="906" height="867" alt="Screenshot 2026-04-20 105414" src="https://github.com/user-attachments/assets/4a4e8d7a-b998-48b6-a1f8-18188dddf987" />



👨‍💻 Author
Siddharth
