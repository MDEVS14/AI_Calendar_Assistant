# JARVIS – AI Calendar Assistant

An AI-powered personal calendar assistant built with **n8n**, integrated with Google Calendar and conversational memory.

Inspired by JARVIS from Iron Man, this project aims to make calendar management intelligent, conversational, and effortless.

## Features

- **Create Events:** Schedule meetings and appointments.
- **Availability Checking:** Check calendar availability before booking.
- **Conflict Detection:** Identify overlapping events.
- **Smart Scheduling:** Find suitable slots based on existing commitments.
- **View Schedule:** Retrieve daily and upcoming events.
- **Update Events:** Modify existing calendar events.
- **Delete Events:** Remove calendar events with confirmation.
- **Conversational Memory:** Retain context across interactions.
- **JARVIS Personality:** A composed, intelligent, and conversational assistant.

## Tech Stack

- n8n – Workflow automation
- Google Calendar API – Calendar management
- AI Agent – Request understanding and decision-making
- LLM – Natural language processing
- Simple Memory – Conversational context

## Architecture

User Request → AI Agent → Chat Model + Memory + Google Calendar Tools → Response

## Getting Started

1. Export the n8n workflow as JSON.
2. Import the workflow into your n8n instance.
3. Configure your Google Calendar credentials.
4. Configure your AI model credentials.
5. Connect the required tools to the AI Agent.
6. Activate the workflow and start interacting with JARVIS.

## Security

- Never upload API keys or credentials.
- Remove personal calendar data before sharing workflow exports.
- Configure your own credentials after importing the workflow.

## Future Improvements

- Voice command integration.
- Speech-to-text and text-to-speech.
- Dedicated web interface.
- Proactive daily briefings.

---

*Building a little closer to having JARVIS manage my day.*
