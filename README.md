# Conversational Chat Assistant with Session Memory

## Overview
This project is a simple conversational chat assistant built using LangChain and OpenAI. The main idea is to make the assistant remember previous messages in a conversation so that responses feel more natural instead of starting fresh every time.

## Motivation
While working with basic chatbots, I noticed that they usually respond only to the current message and ignore what was said earlier. This makes conversations feel disconnected.

To solve this, I implemented a session-based memory system where each conversation keeps its own history. This allows the assistant to refer back to previous messages and maintain context.

## How It Works
- Each user session is assigned a unique session ID  
- A message history is stored for every session  
- Previous messages are automatically passed along with new input  
- The model generates responses based on both current input and past conversation  

## Features
- Maintains conversation context across multiple turns  
- Supports multiple independent sessions  
- Simple and modular design  
- Works in notebook as well as interactive loop  

## Tech Stack
- Python  
- LangChain  
- OpenAI API  
- dotenv  

## Example# context-aware-chat-assistant
A simple chat assistant that remembers past messages in a session to provide more natural and connected responses.
