# Nexa AI Chat

An original MERN AI conversation workspace with an accessible responsive UI, protected chat endpoint, MongoDB conversation model and credential-free demo provider.

## Features

- Conversation workspace with starter prompts and loading feedback
- Provider-neutral chat API contract
- MongoDB-ready conversation history
- Rate limiting, secure headers and request-size protection
- Demo mode requiring no secrets

## Run

```bash
npm install
npm run install:all
npm run dev
```

Use `npm run build` and `npm test` before deployment. Copy `.env.example` to `.env` for persistence and a future AI provider adapter.

## Stack

React, Vite, Node.js, Express, MongoDB, Mongoose and Vitest.

Designed and developed by Pooja Vishnumolakala. Licensed under MIT.

