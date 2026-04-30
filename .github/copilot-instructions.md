# Copilot Instructions

## Project Context
- Backend: Python (FastAPI) under src/backend.
- Frontend: Static assets under src/static.
- Entry point: src/app.py.

## Coding Guidelines
- Keep changes focused and minimal for the requested task.
- Preserve existing naming and file organization.
- Do not add dependencies unless they are necessary.
- Prefer clear, readable code over clever abstractions.

## Backend (Python)
- Follow existing API patterns in src/backend/routers.
- Keep request and response handling explicit.
- Avoid broad exception catching; surface meaningful errors.
- Keep database-related logic consistent with src/backend/database.py.

## Frontend (HTML/CSS/JS)
- Maintain current UI structure and class naming.
- Prefer small, targeted DOM and style updates.
- Keep accessibility in mind (labels, button text, ARIA when needed).

## Testing and Validation
- Run relevant checks after edits when possible.
- If tests are not available, validate by reasoning through affected paths and report what was verified.

## Pull Request Expectations
- Summarize what changed and why.
- Call out risks, follow-ups, and any manual verification steps.
