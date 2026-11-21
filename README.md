# ScholarSphere AI

A hackathon project that brings scholarship, internship, and hackathon discovery into a student dashboard. The app also includes profile and AI copilot views.

This repository forks [adityachavan0007/ScholarSphere-AI](https://github.com/adityachavan0007/ScholarSphere-AI).

## Repository layout

| Path | Purpose |
| --- | --- |
| [vite-project/src](vite-project/src) | React views and Vite entry point |
| [vite-project/src/app/api](vite-project/src/app/api) | Next.js API routes |
| [vite-project/.env.example](vite-project/.env.example) | Configuration placeholders |
| [vite-project/package.json](vite-project/package.json) | Frontend, backend, and build scripts |

## Run locally

Use Node.js 20.9 or later. In `vite-project/`, create a local `.env.local` from the example. Use development Supabase and AI provider settings. Keep service-role and provider keys on the server.

```bash
cd vite-project
npm install
npm run dev
```

From a second terminal in `vite-project/`, run `npm run dev:backend` to start the Next.js backend on port 3001. Vite prints the frontend URL. Use `npm run build` to invoke the combined build.
