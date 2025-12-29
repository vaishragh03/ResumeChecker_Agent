# ResumeChecker_AI_Agent 🤖📄

Automated AI-powered resume evaluation system built with Make.com. Users submit resume links via Telegram bot, get instant ATS-friendly evaluation reports emailed, with real-time Telegram updates.

## 🚀 Features

- **Telegram Bot Trigger**: `/start` + resume Google Docs/Doc link
- **AI Resume Parser**: Extracts content from Google Docs
- **ATS Evaluation**: Scores resume (100-point framework) using AI agent
- **Email Report**: Detailed evaluation sent to user email
- **Real-time Updates**: Telegram notifications during processing

## 📋 Workflow

1. User sends resume link via **ResumeChecker_AI_Agent** Telegram bot
2. Make.com scenario triggers → parses resume content
3. AI evaluates (Format, Keywords, Experience, Skills, etc.)
4. Structured report emailed + Telegram confirmation

## 🛠️ Tech Stack

- **Make.com** (Automation platform)
- **Telegram Bot API**
- **Google Docs API** (Resume parsing)
- **AI Agent** (Resume evaluation)
- **Gmail API** (Report delivery)


## 🔗 Live Demo

**Bot**: `@ResumeChecker_AI_Agent` (search in Telegram)  
**Make Scenario**: [View on Make.com](https://us2.make.com/1713779/scenarios?folder=189571&tab=all)

## ⚙️ Setup (Replicate Yourself)

1. **Make.com Account** (Free tier works)
2. **Create Telegram Bot** (`@BotFather` → `/newbot`)
3. **Import Blueprint** (Download from repo → Scenarios → Import Blueprint)
4. **Connect Services**:
   - Telegram Bot token
   - Google Docs connection
   - Gmail connection
5. **Deploy** → Test with sample resume link

## 📈 Use Cases

- Personal resume optimization
- Mock ATS screening for candidates
- HR team resume pre-screening
- Career coaching feedback tool

## 🤝 Contributing

1. Fork repository
2. Export your Make scenario blueprint
3. Add improvements (better prompts, new parsers, etc.)
4. Submit PR

## 📄 License

MIT License - Feel free to fork, modify, and deploy!

---





