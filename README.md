# Crypto Trading Signal Bot

Real-time trading signals using Renko, Kagi, and Point & Figure charts.

## Setup Instructions

### 1. Add GitHub Secrets
Go to your repository → Settings → Secrets and variables → Actions → Add:

- `TELEGRAM_BOT_TOKEN`: Your bot token from @BotFather
- `TELEGRAM_CHAT_ID`: Your Telegram chat ID

### 2. Enable GitHub Pages
Settings → Pages → Source: "Deploy from branch" → Branch: `gh-pages` /root

### 3. Push to GitHub
```bash
git add .
git commit -m "Initial commit"
git push origin main
