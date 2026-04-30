---
applyTo: "backend/**/*,*.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load development/testing seed data or fixtures from the `database.py` file; do not use this example data in production.
- Log detailed error information on the server, but return sanitized error responses to the frontend with appropriate HTTP status codes and generic messages. Do not expose stack traces, secrets, or other sensitive internal details.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If possible breaking changes are found, mention them to the developer.