🏥 Healthcare Analytics Dashboard
Interactive Streamlit-based dashboard for analyzing hospital operational data. This application displays KPIs, interactive charts, and sidebar filters to monitor healthcare performance dynamically.
🚀 Key Features
✅ 5 Analysis Pages

Executive Dashboard – KPIs and business overview
Operations Analytics – Patient flow optimization
Financial Analytics – Revenue tracking & ROI analysis
Quality Analytics – Service quality and patient experience
Business Recommendations – Strategic initiatives

✅ Dashboard Metrics (Executive Dashboard)

💰 Total Revenue
📦 Total Appointments
📊 Completion Rate
🏥 Average Patient Age

✅ Advanced Filtering System

🔍 Medical Specialization (Multi-select)
📋 Appointment Status (Multi-select)
👥 Patient Gender (Multi-select)
🏢 Insurance Provider (Multi-select)
📅 Patient Age Range (Slider)
💵 Treatment Cost Range (Slider)

🧩 How to Run the Application
1. Clone or Extract the Project
bashgit clone https://github.com/yourusername/healthcare-dashboard
cd healthcare-dashboard
2. (Optional) Create Virtual Environment
bashpython -m venv venv
venv\Scripts\activate          # Windows
source venv/bin/activate       # macOS/Linux
3. Install Dependencies
bashpip install -r requirements.txt
4. Run the Application
bashstreamlit run app.py
5. Access Dashboard in Browser
http://localhost:8501