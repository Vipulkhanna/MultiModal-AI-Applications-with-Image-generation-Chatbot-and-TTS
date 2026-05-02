✈️ FlightAI — Airline AI Assistant (Free Models Edition)

FlightAI is a multimodal AI-powered airline assistant that provides:

💬 Conversational chat (LLM-powered)
💸 Ticket price lookup (via database tool)
🎨 AI-generated travel images
🔊 Text-to-speech responses
🤟 Sign language visualization (ASL-style hand animation)

<img width="1529" height="1720" alt="127 0 0 1_7887__" src="https://github.com/user-attachments/assets/d081e38e-9f5d-4a79-9214-ce12e70476b4" />


This version uses completely free models and APIs, making it easy to run locally without paid OpenAI access.

🚀 Features
💬 AI Chat Assistant
Powered by Groq-hosted LLMs (LLaMA 3 family)
Short, accurate, airline-style responses
Tool-calling support for dynamic responses
💸 Ticket Price Lookup
SQLite database (prices.db)
Function-calling tool retrieves flight prices by city
🎨 Image Generation
Uses Pollinations.ai (no API key required)
Generates destination-themed images dynamically
🔊 Text-to-Speech (TTS)
Powered by Groq Orpheus TTS
Converts assistant responses into audio
🤟 Sign Language Output
Displays animated ASL-style hand gestures
Enhances accessibility
🖥️ Interactive UI
Built with Gradio
Chat interface + image + audio + sign panel

🧠 Models Used
Component	Model
LLM	llama-3.3-70b-versatile (Groq)
TTS	orpheus-v1-english (Groq)
Image	Pollinations.ai (free)

get_ticket_price(city) → queries SQLite DB
artist(city) → generates images
talker(text) → produces audio output
