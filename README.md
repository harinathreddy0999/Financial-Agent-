

# <span style="color:blue;">Financial AI Agent</span>

## 🌟 Overview
This project is a **multi-agent AI system** built using the `phi` framework and `Groq` models. It consists of two agents:

- 🔍 **Web Search Agent**: Fetches information from the web.
- 📈 **Financial Agent**: Retrieves financial data such as stock prices, analyst recommendations, and company news.

## ✨ Features
✅ Utilizes **Groq** models for efficient processing.  
✅ Fetches **real-time** financial data using `YFinanceTools`.  
✅ Retrieves the **latest news** and insights using `DuckDuckGo`.  
✅ Formats data in **tables** for better readability.  
✅ Supports **streaming responses** for real-time insights.  

## 🛠 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-repo/financial-ai-agent.git
cd financial-ai-agent
```

### 2️⃣ Set Up Virtual Environment
```sh
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables
Create a `.env` file and add your API keys:
```
OPENAI_API_KEY=your-openai-api-key
GROQ_API_KEY=your-groq-api-key
```

### 5️⃣ Run the AI Agent
```sh
python FINANCIAL_AGENT.PY
```

## 🚑 Troubleshooting

### 🔴 1. `ModuleNotFoundError: No module named 'groq'`
Run:
```sh
pip install groq
```

### 🔴 2. `openai.OpenAIError: You exceeded your current quota`
- Check your quota: [OpenAI Usage Page](https://platform.openai.com/account/usage)
- Ensure you have an **active payment method**
- Consider **switching to Groq models**

### 🔴 3. `.env file not loading API keys`
- Ensure you have installed `python-dotenv`:
```sh
pip install python-dotenv
```
- Double-check the `.env` file formatting (no spaces around `=`).

## 📜 License
📝 **MIT License**
