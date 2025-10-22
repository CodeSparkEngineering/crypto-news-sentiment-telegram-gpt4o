🧠 Project Overview
This project delivers real-time cryptocurrency news and sentiment analysis via Telegram, powered by GPT-4o and orchestrated through n8n workflows. Users can send a crypto-related keyword or company name through Telegram, and the system responds with a concise summary of relevant news and market sentiment.
🚀 Features

🔍 Aggregates news from multiple crypto RSS feeds (Cointelegraph, Bitcoin Magazine, Coindesk, etc.)
🧠 Uses GPT-4o to analyze and summarize news articles
💬 Telegram bot interface for user interaction
⚙️ Built with n8n for workflow automation

🛠️ Tech Stack

n8n: Workflow automation
OpenAI GPT-4o: Language model for summarization and sentiment analysis
Telegram Bot API: User interface
RSS Feeds: News sources

📲 How It Works

User sends a keyword (e.g., "Bitcoin") to the Telegram bot.
The system fetches articles from various crypto news RSS feeds.
Articles are filtered based on the keyword.
GPT-4o summarizes the news and analyzes market sentiment.
A structured response is sent back to the user via Telegram.

📁 Folder Structure
├── workflows/
│   └── crypto-news-sentiment.json
├── README.md
└── assets/
    └── screenshots/

⚙️ Setup Instructions

Clone the repository:
Shellgit clone https://github.com/yourusername/crypto-news-sentiment-telegram-gpt4o.gitShow more lines

Import the workflow into your n8n instance.
Set up your OpenAI and Telegram credentials.
Deploy and start the Telegram bot.

📸 Example Output
🔹 Summary of News
Bitcoin sees renewed interest as ETF approval nears.

🔹 Market Sentiment
Positive: Analysts predict bullish momentum.

🔹 Sources
- Cointelegraph: [link]
- Bitcoin Magazine: [link]

📬 Contact
For questions or suggestions, feel free to open an issue or reach out via [your contact info].
