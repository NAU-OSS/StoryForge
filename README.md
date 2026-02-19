# StoryForge

StoryForge is an open-source, browser-based interactive storytelling engine that allows creators to build, share, and remix branching narrative worlds.

StoryForge enables writers, developers, and designers to collaboratively create interactive adventures using a node-based structure. Stories are composed of interconnected scenes with choices that branch into multiple outcomes, allowing players to explore dynamic, replayable narratives.

The goal of StoryForge is to provide a lightweight, extensible, and community-driven storytelling platform that encourages creativity and collaboration.

---

## Vision

StoryForge aims to:

- Lower the barrier to creating interactive stories  
- Provide a clean and extensible narrative engine  
- Encourage remixing and forking of community-created worlds  
- Foster an inclusive open-source creative community  

This project is designed to grow through contributions and shared ideas.

---

## Features (v1)

- Create story worlds
- Define scenes (nodes)
- Add branching choices
- Play through interactive stories
- Save story progress
- REST API for story management
- Modular backend architecture

Future features are outlined in the roadmap below.

---

## Architecture Overview

StoryForge follows a client-server architecture:

### Frontend
- React + TypeScript
- Dynamic node rendering
- Responsive UI for story navigation

### Backend
- FastAPI (Python)
- RESTful API
- Modular story engine
- JWT-based authentication

### Database
- PostgreSQL
- Stores users, worlds, scenes, and choices

See `docs/architecture.md` for detailed design documentation.

---

## Installation

### Prerequisites

- Node.js (v18+)
- Python (3.10+)
- PostgreSQL
- Git

---

### Clone the Repository

```bash
git clone https://github.com/NAU-OSS/StoryForge.git
cd StoryForge
