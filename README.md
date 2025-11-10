# 🤖 ChatCPT

**ChatCPT** is a lightweight, frontend-first AI chatbot powered by open-source LLMs running on a mobile device using [Ollama](https://ollama.com/). It supports real-time interaction, daily prompt challenges, and modern UX features like typing animations.

🚀 Live demo[^1]: [https://crymises.github.io/ChatCPT](https://crymises.github.io/ChatCPT/)

---

## 📦 Features

- 🧠 AI chatbot powered by `Kimi K2 Thinking` via Ollama Cloud
- 💬 Typing animation effect for more natural replies
- 🧪 Daily Prompt Challenge via `/challenge` endpoint
- 🧼 Input sanitization and XSS prevention
- 🌐 Deployed frontend on GitHub Pages
- 📡 Ngrok tunneling for local Flask API
- 🗝️ API key + origin restrictions on backend
- 🔐 Rate-limited `/ask` and `/challenge` endpoints
- 💻 Admin dashboard to observe user activity

---

## 🔐 Security & XSS Prevention

- User input is sanitized before sending
- Backend also blocks dangerous patterns (e.g. <script>)
- Protection against unknown origins
- Protection against API spam
- API-KEY to prevent unlicensed user

---

## 📈 Roadmap

- [x] Chat history
- [ ] Markdown rendering for code/formatting
- [ ] Multi-persona AI modes
- [ ] Export chat as text/markdown
- [ ] Voice input support
- [ ] Streamed responses (typewriter + backend support)
- [ ] Upscaling to Qwen3:4b

---

## 📃 License

MIT — free to fork, improve, and remix.


---

🙏 Credits

- Ollama for local LLM hosting
- Deepseek for Deepseek-v3.1
- Ngrok for free tunneling service

---
[^1]: User IP and Chat History are **STORED** but never shared with other parties outside of the development team
