# AI-model-search
A lightweight API enhancement service that adds real-time internet search capabilities to large model APIs.
# DeepSeek2Chatbox | Visualize Thinking Process of SiliconFlow R1

A lightweight API proxy service that reveals DeepSeek model's complete thinking process in Chatbox.

## What is this?
SiliconFlow recently upgraded their API to match DeepSeek's official format, splitting responses into two parts:
- reasoning_content: model's thinking process
- content: final response

This change made Chatbox unable to display the model's reasoning process. This project elegantly merges these two parts through API forwarding, allowing you to experience the model's complete thinking process.

## Getting Started

1. Clone repository
2. Install dependencies:
   ```bash
   pip install flask requests
   ```
3. Start service:
   ```bash
   python server.py
   ```
4. Deploy to server and add SSL
5. Use in Chatbox: `http://your domain name:5000/v1`

## Demo
You'll see output like this:

<think>The user sent a simple greeting. Let me think about how to respond: I should be friendly while maintaining professionalism. Adding appropriate emojis can increase approachability. The response should be concise yet warm, and leave room for further conversation.
</think>

Hello! Nice to meet you 👋 How may I help you today?

## Features
- 🔄 Real-time Forwarding: Zero latency, what you see is what you get
- 🧠 Visible Thinking: AI's reasoning process is no longer a black box
- 🎯 Plug and Play: Fully compatible with Chatbox
- 🪶 Lightweight: No complex configuration needed

## Feedback
Having issues? Feel free to submit an Issue or contact the author. 
