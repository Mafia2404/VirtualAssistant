### 🤖 AssitantAI -A AI Assistant (MERN + AI + Voice)
![ShopAI Banner](https://github.com/Mafia2404/VirtualAssistant/blob/main/frontend/src/assets/image1.jpg) 
Your personal AI assistant with voice interaction, memory, and customizable personality.

🔗 Live Demo:
👉 https://assistantai-wjka.onrender.com

🚀 Key Features
Feature	Description
Voice Interaction	Realistic speech synthesis and recognition using Web Speech API
Smart AI Brain	Gemini AI-powered intelligent responses
User Memory	JWT authentication with bcrypt password hashing
Custom Branding	Upload custom assistant images (Cloudinary + Multer)
Personalization	Change assistant name, voice characteristics, and behavior
Mobile Ready	Fully responsive design works on all devices<br>
### 🛠️ Tech Stack
-Frontend

-React.js

-Web Speech API

-TailwindCSS

-Backend

-Node.js + Express

-MongoDB (Mongoose)

-AI & Services

-Google Gemini API

-Cloudinary (Image Storage)

-JWT + bcryptjs (Authentication)

### Deployment

-Render (Free Tier)
<br>
### 🛠️ Installation Guide
Prerequisites
-Node.js (v18+)

-MongoDB Atlas (Free Tier)

-Google Gemini API Key (Get Here)

-Cloudinary Account (Free Tier)
---
### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/jarvis-ai-assistant.git
cd jarvis-ai-assistant
Step 2: Set Up Backend
bash
cd backend
npm install
Step 3: Set Up Frontend
bash
cd ../client
npm install
```

### Create .env files:
Backend (.env)

```bash
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

```bash
Frontend (.env)

VITE_API_BASE_URL=http://localhost:5000
VITE_ASSISTANT_NAME
Run the application:
bash
# From root directory
npm run dev
```
### 📂 Project Structure
```bash
AssistantAI/
├── backend/
│   ├── controllers/    # AI and auth logic
│   ├── models/         # User schemas
│   ├── routes/         # API endpoints
│   ├── middlewares/    # JWT auth
│   └── server.js       # Express server
├── client/
│   ├── src/
│   │   ├── components/ # Voice UI components
│   │   ├── hooks/      # Custom hooks
│   │   ├── pages/      # Application views
│   │   ├── utils/      # Speech synthesis helpers
│   │   └── App.js      # Main component
├── .gitignore
└── README.md
```

### 🌟 Why This Project?

-✔ Cutting-Edge Tech - Combines AI, voice, and full-stack

-✔ Portfolio Standout - Demonstrates complex integrations

-✔ Fully Customizable - Make it truly your own assistant

-✔ Production Ready - Includes auth, file uploads, and deployment
<br>
🤝 Contributing
Fork the repository

Create your feature branch:

```bash
git checkout -b feature/amazing-feature
Commit your changes:
```
```bash
git commit -m 'Add some amazing feature'
Push to the branch:
```
```bash
git push origin feature/amazing-feature
Open a Pull Request
```
📜 License
MIT ©  AssistantAI 2025
