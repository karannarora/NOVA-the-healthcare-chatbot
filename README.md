# NOVA-the-healthcare-chatbot
## 🩺 Description
The **Healthcare Chatbot** is a locally hosted AI assistant built using **Ollama’s `smollm:1.7b` model**.  
It allows users to ask health-related questions and get intelligent responses **without relying on the cloud** — ensuring full **data privacy**, **offline accessibility**, and **lightweight performance**.  

This setup is ideal for developers who want to run a healthcare-focused AI chatbot on their local system using Ollama.

---

## ⚙️ Setup Commands

```bash
# 1️⃣ Install Ollama using Homebrew
brew install ollama

# 2️⃣ Pull the model
ollama pull smollm:1.7b

# 3️⃣ Run the model
ollama run smollm:1.7b
