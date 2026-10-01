# CodeLearn Community

## Start locally
1. Install Node.js 20+.
2. Copy `.env.example` to `.env` and change `SESSION_SECRET`.
3. Run `npm install`, then `npm start`.
4. Open http://localhost:3000.

## Open-source coding AI
Install Ollama from https://ollama.com, then run `ollama pull qwen2.5-coder:7b`. Start Ollama and configure `OLLAMA_URL` and `OLLAMA_MODEL` in `.env`. The model runs on your own machine; it may need several GB RAM.

## Included
- Homepage, register/login/logout
- SQLite database for accounts, projects, rooms and messages
- Project downloads/search/categories: Mods, Apps, Websites, Minecraft plugins, Extensions, PC/Laptop apps, Other
- Upload files with optional login-required downloads
- Authenticated AI coding chat via Ollama
- Real-time group chat with Socket.IO

## Deployment notes
This is a starter project, not a security-audited production service. For public hosting, use persistent disk/database, HTTPS, backups, rate limiting, moderation/reporting, malware scanning and a secret session key. SQLite and uploaded files need persistent storage on hosting providers. Only upload files you have rights to share.
