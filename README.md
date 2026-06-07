# servicenow-ai-copilot
# AI Incident Copilot (ServiceNow)

An AI-powered ITSM copilot built in ServiceNow using external LLM integration.

## Features
- AI incident summarization
- Priority prediction
- Assignment group recommendation
- KB article recommendation
- Duplicate incident detection

## Architecture
ServiceNow UI Action
→ GlideAjax
→ Script Include
→ Groq API

## Technologies
- ServiceNow
- GlideAjax
- RESTMessageV2
- Groq API
- JavaScript
