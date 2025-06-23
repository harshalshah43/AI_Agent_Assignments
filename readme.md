
# AI Agent Assignments

This project contains code for an AI Travel Agent & Expense Planner using LangGraph and external APIs such as GEOAPIFY and AMADEUS.

## 🌟 Features
- Generates real-time travel itineraries for any city worldwide
- Estimates costs (hotels, attractions, transport, meals)
- Uses AI (LLM) for generating detailed day-by-day plans
- Integrates with multiple APIs for real data

## ⚙️ Environment Variables

Before running, initialize the following environment variables (e.g. in a `.env` file or your environment):

```bash
GEOAPIFY_API_KEY=your_geoapify_api_key
GOOGLE_API_KEY=your_google_api_key
OPENWEATHER_API_KEY=your_openweather_api_key
AMADEUS_CLIENT_ID=your_amadeus_client_id
AMADEUS_CLIENT_SECRET=your_amadeus_client_secret
```

In Python code:
```python
import os

GEOAPIFY_API_KEY = os.getenv("GEOAPIFY_API_KEY")
GOOGLE_API_KEY = os.getenv("GOOGLE_API_KEY")
OPENWEATHER_API_KEY = os.getenv("OPENWEATHER_API_KEY")
AMADEUS_CLIENT_ID = os.getenv("AMADEUS_CLIENT_ID")
AMADEUS_CLIENT_SECRET = os.getenv("AMADEUS_CLIENT_SECRET")
```

## 🚀 How to Run

1️⃣ Make sure you have all dependencies installed:
```bash
pip install -r requirements.txt
```

2️⃣ Run the Jupyter notebook:
```bash
jupyter notebook
```
Then open the notebook file and execute the cells.

## 📂 Structure
- `notebooks/` — Jupyter notebooks with LangGraph workflows
- `src/` — Python modules (if applicable)
- `README.md` — This file

## 💡 Notes
- You must have valid API keys for external services to fetch real-time data.
- You can use a tool like `python-dotenv` to load variables from a `.env` file.

---

Happy hacking! 🚀
