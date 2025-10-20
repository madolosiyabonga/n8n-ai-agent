# 🧠 UMP AI Agent — Powered by n8n

**Sisi UMP** is the official AI Assistant for the University of Mpumalanga.  
It helps students, staff, and visitors find verified information about courses, registration, events, and more — directly through WhatsApp or Telegram.

---

## ✨ Features
- 🤖 AI-powered responses to student queries  
- 🏫 Connects directly with official UMP resources  
- 💬 Accessible on Telegram and WhatsApp  
- 📊 Logs user questions for future FAQ updates  
- 🔒 Secure and built on n8n’s automation engine  

---

## ⚙️ Setup on Render
1. Fork this repo to your GitHub.
2. Go to [Render.com](https://render.com), create a **Web Service**.
3. Connect your GitHub repo → choose “n8n-ai-agent”.
4. Select **Free plan** or Starter ($7/month if you want 24/7 uptime).
5. Add environment variables in Render dashboard:
N8N_BASIC_AUTH_ACTIVE=true
N8N_BASIC_AUTH_USER=admin
N8N_BASIC_AUTH_PASSWORD=yourpassword
WEBHOOK_TUNNEL_URL=https://your-app-name.onrender.com
6. Deploy 🚀
7. Once live, import your `n8n-ai-agent.json` workflow.
8. Paste your Telegram Bot Token inside the Telegram Trigger node.
9. Activate the workflow and start chatting with your bot!

---

## 📱 Telegram Webhook Example
https://api.telegram.org/bot8083752215:AAEJxKBXgrXBDOUz4dgl7_4GVakpVOjhotY<img width="1024" height="1536" alt="ChatGPT Image Oct 7, 2025, 06_45_41 PM" src="https://github.com/user-attachments/assets/d4d304cb-7465-449b-84a1-1e695911b8d7" />
/setWebhook?url=https://your-app-name.onrender.com/webhook/telegram

---

## 🧩 Built With
- **n8n** for automation  
- **Telegram Bot API** for interaction  
- **Render** for hosting  
- **Google Sheets** for logs  

---

## 👨‍💻 Creator
Developed by **Madolo Siyabonga**  
📍 Mbombela, South Africa  
📧 vergesig.ai@outlook.com  
🌍 Powered by AI + Automation
