# Build with the Claude API

Working through Anthropic's [Building with the Claude API](https://anthropic.skilljar.com/claude-with-the-anthropic-api/287725) course.

## Setup
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Create a `.env` file:
```
ANTHROPIC_API_KEY=your-key-here
```

## Topics covered

- API basics & multi-turn conversations
- Prompt engineering & evaluation
- Tool use
- Retrieval augmented generation (RAG)
- Model Context Protocol (MCP)
- Agents & workflows