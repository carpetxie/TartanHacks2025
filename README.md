# EcoSpend! An AI-Powered Carbon Footprint Analyzer

EcoSpend! is a fintech-inspired application created during TartanHacks 2025 by a team of Dartmouth and CMU students. It enables users to monitor and reduce their carbon footprint by analyzing purchase receipts. Using AI-driven receipt parsing and SQL-based analytics, the platform provides real-time estimates of carbon emissions and calculates offset costs to support eco-conscious spending.

---

## Features

- **AI-Powered Receipt Analysis**: Upload receipts to extract purchase details using Google's Gemini AI.
- **Carbon Emission Calculation**: Estimate CO₂ emissions based on product categories, materials, and transportation.
- **Offset Cost Estimation**: Calculate the projected cost to neutralize emissions using current carbon credit pricing.
- **User Accounts & History Tracking**: Secure login system with hashed passwords and carbon score history.
- **SQL-Based Analytics**: Track aggregated carbon impact, trend lines, and user comparisons.
- **Minimalistic Fintech UI**: Built with Streamlit for a clean and intuitive interface.
- **Time-Series Visualization**: View carbon footprint trends over time through interactive charts.

---

## Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python, Google Gemini API  
- **Database**: SQL for authentication, history tracking, and scalable analytics  
- **AI Model**: Google Gemini 1.5 Flash for receipt parsing  
- **Visualization**: Matplotlib and Pandas  

---

## How to Run the Code

First, clone the GitHub repository and set up a Python virtual environment.

### Install Required Libraries
```bash
pip install google-generativeai python-dotenv streamlit pillow matplotlib flask werkzeug
