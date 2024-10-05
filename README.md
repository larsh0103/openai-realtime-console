# Avatar Interaction using OpenAI's Realtime API and Simli Avatar API

This fork utilizes OpenAI's Realtime API in combination with the Simli Avatar API to enable avatar interaction. While still in development, it essentially facilitates video agent conversations.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Resources](#resources)
- [License](#license)

## Introduction

This project demonstrates how to integrate OpenAI's Realtime Voice-to-Voice API with Simli's avatar technology to create interactive video conversations with an AI agent represented by a visual avatar.

## Features

- **Real-time Voice Interaction**: Communicate with the AI assistant using your microphone.
- **Visual Avatar Representation**: The assistant is visually represented using Simli's avatar API.
- **Voice Output**: The assistant responds with synthesized speech.
- **Map Integration**: Demonstrates tool usage like `get_weather()` with map display.
- **Memory Storage**: Uses `set_memory()` to store and retrieve user-specific data.

## Prerequisites

- **Node.js**: Ensure you have Node.js installed (version 12 or higher).
- **API Keys**: You need API keys for both OpenAI and Simli services.

## Installation

1. Clone the Repository

   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject
   npm install
```

## Configuration

Create a .env File

In the root directory of the project, create a file named .env.
Add Your API Keys
Add your OpenAI and Simli API keys to the .env file: 

```
REACT_APP_OPENAI_API_KEY=your_openai_api_key
REACT_APP_SIMLI_API_KEY=your_simli_api_key
```

Replace your_openai_api_key and your_simli_api_key with your actual API keys.
Note: Keep your API keys secure and do not commit the .env file to version control.

## Usage

Start the Application
bashCopynpm start
The application will run on http://localhost:3000.
Interact with the Assistant

Connect: Click on the Connect button to establish a connection.
Push to Talk: Use the Push to Talk button to start speaking to the assistant.
View Avatar: The Simli avatar will appear, representing the AI assistant.
Use Tools: Try out tools like get_weather() and set_memory() within the conversation.



Resources
OpenAI Realtime API

Documentation: OpenAI Realtime Voice-to-Voice API
API Reference: OpenAI API Reference

Simli Avatar API

Website: Simli.ai
Documentation: Simli Developer Docs