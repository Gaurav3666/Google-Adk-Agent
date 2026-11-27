# Google-Adk-Agent
# Google-Adk-Agent

A conversational AI chatbot built using **Google ADK (Agent Development Kit)** and powered by **Google Gemini**.

## Project Structure

```text
Agents/
└── groot/
    ├── __init__.py
    ├── agent.py
    ├── .env
    ├── .gitignore
    └── README.md
```

## Features

- Built with Google's official Agent Development Kit (`google-adk`)
- Powered by Gemini LLM for natural, context-aware conversations
- Interactive web UI and CLI testing support via ADK runner

## Prerequisites

- Python 3.10 or higher
- A Google Gemini API Key from [Google AI Studio](https://aistudio.google.com/)

## Setup & Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/Gaurav3666/Google-Adk-Agent.git](https://github.com/Gaurav3666/Google-Adk-Agent.git)
   cd Google-Adk-Agent
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install google-adk
   ```

4. **Configure environment variables**
   Create a `.env` file inside the `groot/` directory and add your Gemini API key:
   ```env
   GOOGLE_GENAI_USE_VERTEXAI=FALSE
   GOOGLE_API_KEY=your_gemini_api_key_here
   ```

## Usage

Run the agent using the ADK web interface or terminal from the parent `Agents` directory:

- **Web UI:**
  ```bash
  adk web
  ```
- **Terminal / CLI:**
  ```bash
  adk run groot
  ```
