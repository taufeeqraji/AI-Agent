# 🏠 RentWise – AI-Powered Rental Assistant
RentWise is an AI agent application built to simplify the rental search process. Users can describe what they’re looking for in a home, and RentWise will intelligently search real-time listings, process them, and return personalized rental recommendations — all through a conversational interface.

Built as part of the AI Agent Real-World Application Challenge, RentWise leverages low-code tools like Langflow, OpenAI GPT-4o, and live web scraping APIs to deliver a seamless rental search experience.

# 🚀 Features
🔍 Real-Time Rental Search using Firecrawl Scrape API
🧠 Natural Language Interaction powered by OpenAI GPT-4o
📝 Text Parsing & Aggregation from multiple rental websites
🧩 Langchain Components for context-aware prompt building
💬 Chat Interface for easy user interaction
🌐 Google Maps Integration (optional, for future use)

# 🧱 System Architecture (LangFlow Components)
1. Firecrawl Scrape API – Pulls data from rental websites like Rentfaster, Zumper, etc.
2. Parser – Converts raw scraped data into clean text.
3. Combine Text – Aggregates multiple parsed site contents into one unified source.
4. Prompt Template – Injects listing data and user query into the LLM.
5. OpenAI GPT-4o – Interprets the input and returns filtered, ranked rental options.
6. Chat Input / Output – Simple UI for user messages and responses.

# 🛠️ Setup & Installation
Note: This project is built using Langflow, so it doesn't require conventional code deployment.

To run this project locally (if using custom Python tools):
'''
git clone https://github.com/taufeeqraji/rentwise.git
cd rentwise
'''

To replicate using Langflow:

1. Import the .json file (Langflow chain) into your Langflow UI
2. Connect your OpenAI and Firecrawl API keys
3. Hit Run and start chatting!

