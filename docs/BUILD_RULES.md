# Framehouse Build Rules

## 1. Small Tasks Only

Each AI build task should focus on one small change.

Good:
- Add the Story data model.
- Add a GET /stories endpoint.
- Create the story review list UI.

Bad:
- Build the whole Framehouse app.
- Create the editor, scraper, dashboard and AI pipeline in one go.

## 2. Minimal Patches

Do not rewrite unrelated files.
Do not restructure the project unless the task explicitly asks for it.
Do not introduce new frameworks without explaining why.

## 3. Prototype First

The first milestone is Framehouse Stories, not the full editor.

The goal is to create a useful story discovery and review system before building timeline editing or motion graphics.

## 4. Local First

The prototype should run locally on the user's machine.

Use SQLite for the initial database.
Avoid cloud dependencies unless explicitly requested.

## 5. Human Editorial Control

Framehouse should help discover and prepare content, but the user decides what to approve, reject or publish.

## 6. AI Efficiency

Do not rely on huge prompts.
Use project docs for stable context.
Use small implementation prompts.
Start new AI chats when changing task area.

## 7. Acceptance Criteria

Every build task should include acceptance criteria.

Example:

- The app starts without errors.
- A story can be created.
- Stories can be listed.
- Tests pass.
- No unrelated files are changed.