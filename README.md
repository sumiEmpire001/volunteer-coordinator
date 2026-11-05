# Volunteer Coordinator

A responsive volunteer shift planner built with HTML, CSS and vanilla JavaScript. Create dated shifts, set volunteer capacity, assign volunteers, remove assignments, and view staffing totals. The app prevents duplicate assignments and overbooking within its local dataset.

## Run

Start `python -m http.server 8000` and open http://localhost:8000.

## Tests

Requires Node.js 18+. Run `npm test` for eight tests. CI runs them on pull requests.

## Scope

All data stays in this browser's localStorage. No multi-user coordination, authentication, reminders, or shared server is included. Use as a prototype rather than a real volunteer scheduling service.
