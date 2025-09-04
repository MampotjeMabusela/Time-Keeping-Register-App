# Time-Keeping-Register-App

🕒 Time-Keeping Register App
A lightweight, Python-based time-tracking tool built in Jupyter Notebook for logging work sessions, calculating durations, and exporting entries to CSV. Ideal for freelancers, remote teams, and compliance-conscious professionals who need a simple, auditable time register.

📌 Features
✅ Log start and end times with timestamps

⏱️ Auto-calculate session duration in minutes

📁 Save entries to a persistent CSV file

📊 View recent logs directly in the notebook

🔒 Designed with auditability and data transparency in mind

🛠️ Tech Stack
Component	Description
Python	Core logic and time handling
Pandas	Data manipulation and CSV export
Jupyter Notebook	Interactive execution and logging
CSV	Lightweight, portable data storage
🚀 Getting Started
1. Clone the Repository
bash
git clone https://github.com/MampotjeMabusela/Time-Keeping-Register-App.git
cd Time-Keeping-Register-App
2. Launch Jupyter Notebook
bash
jupyter notebook
Open Time-Keeping Register App.ipynb and run cells sequentially.

📋 Usage
Log a Start Time
python
user_entry = log_start("Your Name")
Log an End Time
python
user_entry = log_end(user_entry)
Save the Entry
python
save_entry(user_entry)
View Recent Logs
python
df.tail()
📂 File Structure
Code
Time-Keeping-Register-App/
│
├── README.md
├── time_register.csv         # Auto-generated log file
└── Time-Keeping Register App.ipynb
🧠 Future Enhancements
🔐 User authentication

📈 Dashboard visualizations with Plotly or Streamlit

🌍 POPIA/GDPR-compliant logging for enterprise use

☁️ Cloud sync and multi-user support

👤 Author
Mampotje Mabusela Aspiring AI Specialist | Legal Tech Innovator | Compliance Strategist 📍 Gauteng, South Africa | Open to relocation and remote work 🔗 LinkedIn
