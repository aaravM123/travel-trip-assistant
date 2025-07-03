
# 🌍 Travel Assistant: AI-Powered Global Trip Assistant

This assistant uses LangChain and OpenAI to:
- Get **real-time weather** for any city
- Show a **5-day forecast** with highs/lows and conditions
- Convert **time zones** across major cities

## Example Prompts
- “What’s the weather in Tokyo right now?”
- “Give me the 5-day forecast for San Francisco.”
- “What time is 3 PM in New York in London?”
- “What’s the current weather and time difference between Barcelona and Tokyo?”

## Features
- 🌤️ Real-time weather data using Open-Meteo and OpenStreetMap
- 📆 5-day forecast with daily highs/lows and weather codes
- 🕓 Time zone conversion across global cities (NYC, Tokyo, Barcelona, etc.)
- 🤖 Agent-based reasoning using LangChain
- 💬 Streaming GPT responses via callback handler

## Run Instructions
```bash
pip install langchain langchain-openai langchain-community requests pytz 