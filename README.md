🚀 Advanced SOC Port Scanner & AI Analyzer
📌 Overview

This project is a Python-based Advanced Port Scanner with a Graphical User Interface (GUI) built using Tkinter.
It scans open ports on a target system and uses AI (Google Gemini) to generate a security analysis report.

✨ Features
🔍 Port Scanning
Scan any IP address or hostname
Custom port range (0–65535)
Multi-threaded scanning (fast performance)
Detects:
Open ports
Running services
Service banners
⚡ Performance Modes
🐢 Stealth Mode (10 threads)
⚖️ Normal Mode (100 threads)
🚀 Aggressive Mode (800 threads)
🎨 Smart GUI (Tkinter)
User-friendly interface
Live scan progress bar
Real-time results table
Color-based risk visualization:
🔴 High Risk
🟠 Medium Risk
🟢 Secure
🤖 AI Security Analysis
Uses Google Gemini API
Generates:
Vulnerability assessment
Risk analysis
Mitigation steps
📁 Export Options
Export scan results → CSV
Export AI report → TXT / Markdown
🛠️ Technologies Used
Python 3
Tkinter (GUI)
Socket Programming
Multithreading (concurrent.futures)
Google Gemini AI (google-generativeai)
dotenv (for secure API keys)
📂 Project Structure
project/
│
├── main.py
├── .env
├── requirements.txt
└── README.md
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/port-scanner-ai.git
cd port-scanner-ai
2️⃣ Install Dependencies
pip install -r requirements.txt
🔑 Setup API Key

Create a .env file:

GEMINI_API_KEY=your_api_key_here

⚠️ Never upload your API key to GitHub.

▶️ Run the Application
python main.py
🧠 How It Works
User enters:
Target IP/Host
Port range
Scanner:
Uses sockets to check open ports
Uses threads for speed
Banner grabbing:
Identifies services running
AI Analysis:
Sends scan data to Gemini
Generates security report
📊 Example Output
Port	Service	Banner
80	HTTP	Apache Server
22	SSH	OpenSSH 7.6
443	HTTPS	Secure
