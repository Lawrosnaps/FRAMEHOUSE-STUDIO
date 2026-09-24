# AI Builder Context

You are helping build Framehouse.

Framehouse is a creator operating system for discovering, preparing, editing and publishing video content.

The first product module is Framehouse Stories.

Framehouse Stories is a local web app that collects possible content stories into a holding database, then lets the user review, approve, reject and develop those stories.

The prototype niche is UK policing content, especially for UK Cop Humour-style commentary, explainers and social/video content.

The system should support broad UK policing story discovery, including:

- policing news
- viral police videos
- police auditor content
- public order incidents
- policy changes
- misinformation or controversial claims
- public commentary about policing
- explainers around police powers and operational context
- humorous or serious content opportunities

The long-term goal is for users to define any niche, such as Minecraft, Marvel, football, tech reviews or true crime, and have Framehouse help them discover current content opportunities in that niche.

The build should be modular.

Do not build the full video editor yet.

The first milestone is:

1. A backend API.
2. A local SQLite database.
3. A Story data model.
4. A simple review dashboard.
5. Status workflow for stories.
6. Ability to add sample stories manually or from simple collectors.
7. Later expansion into research packs, scripts, media collection and video editing.

Recommended prototype stack:

- Python
- FastAPI
- SQLite
- SQLModel or SQLAlchemy
- React
- TypeScript
- Vite
- Tailwind CSS

Important build rules:

- Keep changes small.
- Do not redesign the whole project unless asked.
- Do not add unnecessary features.
- Do not rewrite unrelated files.
- Prefer working, simple, testable code over clever abstractions.
- Every task should have clear acceptance criteria.
- If something is ambiguous, make a reasonable assumption and state it briefly.