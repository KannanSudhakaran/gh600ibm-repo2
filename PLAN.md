# Plan: GH600 Hello App

## Goal
Simple Node.js web app serving an index page that greets "Hello to all GH600 IBM folks".

## Steps
1. Scaffold Node.js project (package.json) using Express.
2. Create `server.js` with a single route `/` serving an HTML page.
3. Create `public/index.html` (or inline HTML) with the greeting message.
4. Add `npm start` script.
5. Install dependencies (express).
6. Run the server and verify via curl/browser that it returns the greeting.

## Tech Stack
- Node.js
- Express.js (minimal web framework)

## Verification
- Start server with `npm start`
- `curl http://localhost:3000/` returns page containing "Hello to all GH600 IBM folks"
