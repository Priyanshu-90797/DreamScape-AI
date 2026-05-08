DreamScape AI 🌌
An AI-powered cinematic content generation platform that transforms emotions, thoughts, and prompts into immersive visual experiences using AI-generated imagery, cinematic video processing, and intelligent background music integration.

🌌 Overview
DreamScape AI is a full-stack AI multimedia generation project designed to create emotionally driven cinematic experiences. The platform analyzes user emotions from text prompts, generates visually immersive scenes, fetches cinematic footage, adds dynamic background music, and merges everything into a final cinematic output.
The project combines AI creativity, multimedia processing, and modern web technologies into one seamless workflow.

✨ Features
🎭 Emotion Detection & Sentiment Analysis
🖼️ AI Image Generation
🎥 Cinematic Video Creation
🎵 Background Music Integration
🌧️ Mood-Based Scene Generation
🌌 Fantasy, Cyberpunk, Anime & Nature Themes
⚡ FastAPI Backend
⚛️ React + Vite Frontend
🎬 Automatic Video + Audio Merging
📽️ Cinematic Video Fetching using Pexels
🎨 Intelligent Prompt Engineering

🛠️ Tech Stack
Frontend
React.js
Vite
Axios
Tailwind CSS
Backend
FastAPI
Python
MoviePy
Pillow
NumPy
yt-dlp
AI & Multimedia Tools
Stable Diffusion
Prompt Engineering
Pexels API
FFmpeg
AI Media Processing



📂 Project Structure
DreamScape-AI/│├── backend/│   ├── src/│   │   ├── ai_core/│   │   ├── routes/│   │   ├── services/│   │   └── utils/│   ││   ├── outputs/│   ├── requirements.txt│   └── main.py│├── frontend/│   ├── src/│   ├── public/│   ├── package.json│   └── vite.config.js│├── README.md└── .gitignore

🎬 Generation Workflow
User Prompt     ↓Emotion Analysis     ↓AI Prompt Generation     ↓AI Image Generation     ↓Cinematic Video Fetching     ↓Background Music Download     ↓Video + Audio Merging     ↓Final Cinematic Output

🚀 Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/Priyanshu-90797/DreamScape-AI.gitcd DreamScape-AI

🔧 Backend Setup
Navigate to backend
cd backend
Install dependencies
pip install -r requirements.txt
Run backend server
uvicorn main:app --reload
Backend runs on:
http://127.0.0.1:8000

⚛️ Frontend Setup
Open a new terminal
cd frontend
Install frontend dependencies
npm install
Run frontend
npm run dev
Frontend runs on:
http://localhost:5173

🔗 Frontend ↔ Backend Connection
Inside api.js:
const API_BASE_URL = 'http://127.0.0.1:8000/api/v1'

🌄 Example Prompts
Cozy Cyberpunk Rain
A cozy cyberpunk cafe during heavy rain at night, neon reflections, cinematic atmosphere, ultra detailed, relaxing mood, 4k
Fantasy Mountains
Massive snowy mountains above the clouds during golden sunrise, cinematic drone shot, atmospheric fog, ultra realistic, breathtaking scenery
Peaceful Nature
A peaceful mountain lake during sunrise with soft wind and birds flying, calming atmosphere, cinematic slow motion, ultra realistic
Futuristic Cyberpunk City
A futuristic cyberpunk city with neon holograms, flying cars, cinematic drone shot, ultra realistic lighting, atmospheric reflections, 4k

📦 Requirements
Python 3.10+
Node.js
FFmpeg
Git

📸 Future Enhancements
Real AI Video Generation
Stable Video Diffusion Integration
Runway ML Integration
AI Voice Narration
Cloud Deployment
User Authentication
Advanced Cinematic Effects
Real-Time Rendering
Multi-language Support

🤝 Contributing
Contributions, ideas, and suggestions are welcome.

📄 License
This project is intended for educational and portfolio purposes.

👨‍💻 Author
Priyanshu Khandelwal
AI Enthusiast • Full Stack Developer • Data Science & AI Explorer 🚀
