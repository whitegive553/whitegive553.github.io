---
title: "Interactive Game Server"
excerpt: "WebSocket-based multiplayer games and LLM-powered interactive adventures hosted on personal server"
collection: portfolio
---

## Overview
A personal game server hosting experimental multiplayer and AI-driven games. The server showcases real-time communication technologies and creative applications of large language models in interactive entertainment.

**Live Server**: [http://47.101.202.126/](http://47.101.202.126/)

---

## Available Games

### 1. Avalon (The Resistance: Avalon)
**Status**: ✅ **Live and Playable**

A browser-based, WebSocket-powered implementation of the social deduction game *The Resistance: Avalon*.

**Features**:
- **Real-time multiplayer**: WebSocket-based communication for low-latency gameplay
- **Core Avalon mechanics**: Role assignment, mission voting, team approval, and assassination phase
- **Multi-room support**: Multiple games can run concurrently
- **Web-based access**: No installation required

**Technical Highlights**:
- WebSocket protocol for real-time player interactions
- Server-side authoritative game state
- Event-driven architecture for turn-based progression

---

### 2. LLM-Powered Conversation Adventure Game
**Status**: 🚧 **In Development (Local Prototype Ready)**

An experimental text-based adventure game designed around LLM-driven narrative generation and structured player choices.

**Current Progress**:
- ✅ Core conversation flow implemented
- ✅ Local LLM pipeline validated (development environment only)
- ✅ Initial game loop functional
- 🔄 Expanding storyline scripts and scene definitions
- 🔄 Improving pacing control and choice consequence tracking

**Deployment Note (Important)**:
- The LLM feature is currently **enabled only in local / development environments**.
- The **public server does not yet connect to an external LLM API**, due to:
  - Cost control considerations
  - API key security and abuse prevention
  - The need for a hardened prompt and context management pipeline
- On the live server, this game may run in a **scripted or placeholder mode** until the LLM gateway is deployed.

**Design Vision**:
- Scene-driven narrative generation with structured context input
- Branching storylines with persistent consequences
- Controlled narrative pacing to avoid non-progressive responses
- Natural language interaction once the online LLM service is enabled

---

## Web Client Compatibility

This project is delivered as a **pure web application**, accessible from modern browsers:

- **Desktop**: Chrome, Edge, Safari
- **Mobile**: iOS Safari, Android Chrome

The UI is designed to support both desktop and mobile browsers. Layouts and interactions are responsive and will continue to be optimized for different screen sizes and input methods.

---

## Technologies

**Backend**:
- WebSocket for real-time multiplayer communication
- RESTful APIs for authentication and session management
- Modular game architecture supporting multiple game types

**Frontend**:
- Browser-based UI (no installation required)
- Responsive layout for desktop and mobile
- Real-time updates via WebSocket

**Infrastructure**:
- Self-hosted server deployment
- Concurrent game room management
- Session and game state persistence

---

## Try It Out

Live server (HTTP, development stage):
http://47.101.202.126/

- Avalon is live and fully playable.
- The LLM adventure game is under active development; online LLM calls are not enabled yet.

---

## Feedback

This is an ongoing experimental project.  
Suggestions, bug reports, and feedback are welcome.

**Email**: pengze.ai@mail.utoronto.ca

---

## Try It Out

Visit the live server: **[http://47.101.202.126/](http://47.101.202.126/)**

Start a game of Avalon with friends or explore the LLM adventure game as development continues!
