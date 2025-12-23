🚀 Live Demo
Check out the live app here: bitebotai.streamlit.app

✨ Features
Visual Pantry (Multimodal): Upload a photo of your fridge or ingredients, and the AI "sees" what you have.

Speed-Centric: All recipes are optimized for 5, 10, or 15-minute preparation times.

Regional Nuance: Expertly handles Indian ingredients, spices, and "speed-hacks" (like using a microwave for par-boiling).

Dietary Filters: Supports Non-Veg, Veg, Jain, and Vegan preferences.

Mobile-First Design: Light-mode optimized for easy reading while cooking in the kitchen.

🛠️ Tech Stack
AI Engine: Google Gemini 3 Flash (Latest low-latency multimodal model).

Framework: Streamlit for the web interface.

Language: Python 3.10+.

Deployment: Streamlit Community Cloud.

🧠 AI Learnings (PM Perspective)
Latency vs. Accuracy: Chose the Flash model series to ensure near-instant responses, as speed is the primary value proposition for the target user.

Prompt Engineering: Developed structured system instructions to enforce strict formatting and "Bite-Hack" shortcuts.

Computer Vision: Implemented multimodal processing to reduce user friction (Image-to-Recipe vs. manual typing).

💻 Local Setup
Clone the repo:

Bash

git clone https://github.com/your-username/bitebot-ai.git
cd bitebot-ai
Install dependencies:

Bash

pip install -r requirements.txt
Set up Secrets: Create a .streamlit/secrets.toml file and add your Gemini API Key:

Ini, TOML

GEMINI_API_KEY = "your_key_here"
Run the app:

Bash

streamlit run bitebot.py
Made with ❤️ for Food x AI — Abhinav
