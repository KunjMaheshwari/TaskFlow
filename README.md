# TaskFlow

Minimal todo application built with **Convex**.

## Overview
TaskFlow is a lightweight task manager focused on fast task capture and simple organization.

## Tech Stack
- TypeScript
- Convex
- CSS

## Features
- Create, update, and delete todos
- Mark tasks as complete / incomplete
- Real-time data sync powered by Convex

## Getting Started

### Prerequisites
- Node.js (LTS recommended)
- A Convex account / project

### Install
```bash
npm install
```

### Run locally
```bash
npm run dev
```

### Convex setup
Initialize and run Convex (first time and during development):
```bash
npx convex dev
```

## Scripts
- `npm run dev` – start the development server
- `npm run build` – build for production
- `npm run start` – start the production server (if configured)

## Deployment
Deploy the Convex backend:
```bash
npx convex deploy
```

Deploy the frontend using your preferred hosting provider (Vercel, Netlify, etc.).

## Project Structure
Repository structure may vary by framework, but typically:
- `src/` – application source
- `convex/` – Convex functions and schema
- `public/` – static assets
