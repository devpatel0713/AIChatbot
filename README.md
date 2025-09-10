# AI Chatbot (Angular)

This is a simple AI-powered chatbot built with **Angular**.  
It allows users to send prompts to different AI providers — **OpenAI**, **Hugging Face**, or a built-in **Demo API** — and view AI-generated responses.

---

## Features
- Switch between **Demo**, **OpenAI**, and **Hugging Face** providers  
- Enter custom **API keys** for OpenAI or Hugging Face  
- Submit chat prompts and receive responses in real time  
- Demo mode for testing without API keys  
- Form validation (e.g., requires a minimum 3-character prompt)  

---

## Tech Stack
- **Angular** (standalone components, Reactive Forms)  
- **RxJS**  
- **HTTP Client** (for API calls)  
- **TypeScript**  

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/devpatel0713/AIChatbot.git
cd AIChatbot
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
ng serve
Open http://localhost:4200 in your browser.
```
## API Keys

Demo provider: Works without any keys.

OpenAI: Requires an API key from OpenAI Dashboard

Hugging Face: Requires an API key from Hugging Face

API keys can be entered directly into the app’s input field when the respective provider is selected.

## Notes

Free OpenAI trial credits expire after 3 months. You may need to add billing for continued use.

Hugging Face inference models may require a Pro subscription for heavy usage.

Demo mode simulates responses and does not require an internet connection.
