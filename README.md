🌟 Afiora Care – Accessibility AI Agent
AI-Powered Healthcare Companion for Blind Users, PwD & Elderly Patients

Afiora Care is a healthcare accessibility AI agent designed to support blind users, low-vision individuals, elderly patients, and persons with disabilities.

It reads medical documents, provides calming emotional support, finds verified volunteers, triggers emergency SOS, and shows accessibility-friendly hospitals — all in one place.

This project combines a live backend AI agent on Hugging Face + a clean healthcare UI built with Lovable.

🚀 Live Demo
🔹 Frontend Web App (Lovable UI)

👉 https://afiora-care-buddy.lovable.app/assistant

🔹 Backend AI Agent (Hugging Face Space)

👉 https://huggingface.co/spaces/mehwishafsa/afiora-accessibility

Both links are fully functional and can be demoed instantly.

🧠 Core Features
📄 1. OCR + Speech Reader

Upload prescriptions, lab reports, medical bills

OCR extracts text using pytesseract

Text is simplified into easy language

Browser TTS reads the simplified output aloud

Extremely useful for blind/low-vision patients

📷 2. Live Real-Time Camera OCR

Uses webcam

Reads labels, signs, room numbers, boards in real-time

Helps blind users navigate hospitals independently

💙 3. Calm Mode (Emotional Support Chat)

Gentle emotional support chatbot

Helps users experiencing anxiety or panic in hospitals

Provides breathing reminders, reassurance, and calm replies

Designed for PwD and elderly patients

👐 4. Volunteer Connect

Enter your area or location

Shows available volunteers nearby

Volunteers can help with hospital visits, walking support, document reading, wheelchair support

Uses simple rule-based matching

🚨 5. SOS Emergency Trigger

Big red SOS button for urgent situations

Simulates sending alerts to caregivers

Turns screen red for visibility

Logs emergency timestamp

🗺️ 6. Accessibility Map

Search hospitals by city

Shows accessibility score (ramps, lifts, noise levels, wheelchair paths)

Embedded Google Maps preview

Helps PwD choose safe & accessible hospitals

🔧 Tech Stack
Frontend (Web App) — Lovable

HTML + CSS + JavaScript

Lovable App Builder

Responsive design (mobile + desktop)

Healthcare UI theme

Browser Speech Synthesis API

Fetch + Gradio JS client for API calls

Backend (AI Agent) — Hugging Face

Python

Gradio

OpenCV

pytesseract

Rule-based AI (Calm Mode)

Real-time OCR

HTML map embedding

🔗 API Endpoints (HuggingFace Space)

Base URL:

https://mehwishafsa-afiora-accessibility.hf.space/

Feature	Endpoint	Input	Output
OCR + Speech	/process_ocr	Image	[Extracted text, Simplified text]
Live OCR	/live_ocr	Webcam frame	Text
Calm Mode	/calm_reply	Message	Supportive reply
Volunteer Connect	/find_volunteer	Area	List of volunteers
SOS	/sos_trigger	Boolean	Confirmation
Accessibility Map	/search_hospital	City	Info + Map iframe
🏗 System Architecture
           User (Browser)
                |
                |   Uploads photo / sends message
                v
     --------------------------------
    |       Lovable Frontend UI      |
    |  (OCR Tab, Calm Mode, SOS etc) |
     --------------------------------
                |
                |  API Calls via @gradio/client
                v
     --------------------------------
    |  Hugging Face AI Agent Backend |
    |   OCR, Simplification, Maps     |
     --------------------------------
                |
                v
          AI Output (Text/Voice/Map)


🏆 Why Afiora Care Matters

Helps blind users read critical medical documents

Reduces hospital anxiety

Connects patients with volunteers

Increases accessibility in healthcare

High social impact project (SDG 3: Good Health & Well-Being)

Ideal for Imagine Cup, SIH, WE-Hub, T-Hub, Smart Hackathons

👩‍💻 Developer

Mehwish Afsa
AI Enthusiast • Accessibility Innovator • Healthcare Tech Developer

📝 License

MIT License

🙌 Contributions

Pull requests are welcome! If you'd like to improve Afiora Care, feel free to submit issues or enhancements.

📢 Star This Repo

If you find Afiora Care inspiring or useful, please ⭐ the repository — it supports future development.

🎉 THANK YOU FOR USING AFIORA CARE

Making healthcare more accessible, one AI agent at a time. 💙
