🧠 Skin Disease AI Detector
  

🌐 Live Demo
🔗 melanoma-lesion-dedector.onrender.com

💡 What It Does
📸 Upload or click a picture of your skin
🔍 Gemini AI detects diseases or confirms healthy skin
🤖 Chatbot asks interactive questions to verify the diagnosis
👩‍⚕️ Suggests doctor consultation if symptoms don’t match
🛠️ Tech Stack
Technology	Role
Streamlit	Web UI
Gemini API	Image & Chat Intelligence
Python	Main backend language
Pillow (PIL)	Image processing
dotenv	Manage secrets safely
📁 Project Structure
├── main.py # Streamlit App ├── chat.py # Gemini chat logic ├── requirements.txt # Dependencies ├── .env # API key (keep secret!) └── README.md # You're here

🚀 Getting Started Locally

Clone the repo bash Copy Edit git clone https://github.com/HARINII2415/skin-disease-ai.git cd skin-disease-ai
Create and activate virtual environment (optional) bash Copy Edit python -m venv venv source venv/bin/activate # Windows: venv\Scripts\activate
Install dependencies bash Copy Edit pip install -r requirements.txt
Create .env file bash Copy Edit echo "GEMINI_API_KEY=your_api_key_here" > .env
Run the app bash Copy Edit streamlit run main.py 🎯 Use Case This tool is ideal for:
Early skin condition awareness

AI-assisted dermatology prototypes

HealthTech hackathons or student AI projects

🙋‍♀️ Developed by Jeysri V 🎓 4th-year B.Tech IT Student 💻 Passionate about AI, Full Stack Development, and HealthTech

🌐 LinkedIn • 💼 Portfolio

🛑 Disclaimer ⚠️ This is a demo tool and does not provide medical advice. For accurate diagnosis and treatment, consult a medical professional.
⭐ Show Some Love If this helped or inspired you:

⭐ Star this repo 🖊️ Fork & contribute 🔁 Share with friends

🔮 Upcoming Ideas ✅ Email report feature

✅ Multi-disease detection

🎨 Better UI using Tailwind / CSS

📊 Symptom analytics dashboard
