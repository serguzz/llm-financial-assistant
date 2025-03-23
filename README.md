# 📈 LLM-Powered Financial Market News & Trading Signal Assistant

## 📝 Overview
This project uses an **offline LLM model (h2oGPT)** to analyze financial news, extract sentiment, and generate trading signals using **CatBoost**. No API calls—everything runs locally!

## 🔥 Features
✅ **Offline LLM Processing** – No reliance on external APIs  
✅ **Financial News Sentiment Analysis** – Uses FinBERT/h2oGPT for NLP tasks  
✅ **CatBoost Trading Signal Model** – Predicts buy/sell signals based on news sentiment  
✅ **Historical Data Correlation** – Evaluates how sentiment affects asset prices  
✅ **Local Dashboard & API** – Monitor insights via a UI and FastAPI  

## ⚙️ Tech Stack
- **LLM**: h2oGPT, FinBERT (for sentiment analysis)
- **ML Model**: CatBoost (for trading signal prediction)
- **Data**: Scraped/downloaded financial news & historical market data
- **Backend**: FastAPI (for local API)
- **UI**: Streamlit/Dash (for visualization)

## 🚀 Setup & Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/serguzz/llm-financial-assistant.git
cd llm-financial-assistant
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Download & Set Up Models
```bash
bash scripts/download_models.sh
```

### 4️⃣ Run the Application
```bash
python src/app.py  # Start API
python ui/dashboard.py  # Launch UI
```

## 📊 Usage
- **News Analysis**: Scrape news & analyze sentiment
- **Trading Signal Generation**: Predict market movements using CatBoost
- **LLM Queries**: Ask financial-related questions via h2oGPT

## 📌 Future Enhancements
- [ ] Fine-tune h2oGPT on financial datasets
- [ ] Add real-time stock market integration
- [ ] Improve CatBoost model with more features

## 📜 License
MIT License - Free to use & modify!

---
🚀 **Contributions & feedback welcome!** Open an issue or PR. 💡

