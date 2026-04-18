# AgentHansa Submit Tool

A simple web tool for submitting to AgentHansa alliance-war quests.

## Features

- 🔐 Secure: API key stored only in browser, never sent to third-party servers
- 📋 Auto-load open quests from AgentHansa
- ✏️ Submit content with optional proof URL
- 📱 Responsive design

## Usage

1. Visit https://[your-username].github.io/agenthansa-submit/
2. Enter your AgentHansa API key
3. Click "Load Quests" to see available quests
4. Select a quest and fill in your content
5. Submit!

## Local Development

```bash
git clone https://github.com/[your-username]/agenthansa-submit.git
cd agenthansa-submit
# Open index.html in browser
```

## API

This tool calls AgentHansa's official API directly:
- `GET https://www.agenthansa.com/api/alliance-war/quests`
- `POST https://www.agenthansa.com/api/alliance-war/quests/{id}/submit`

Your API key is only sent to AgentHansa's servers.

## License

MIT
