# deneme-testi

A modern full-stack application built with Better-T-Stack.

## Stack

TypeScript, Next.js, Hono, Drizzle, PostgreSQL, Better-Auth

## Quick Start

Install dependencies:
```bash
bun install
```

Set up your database and push the schema:
```bash
bun db:push
```

Start development:
```bash
bun dev
```

Visit [localhost:3001](http://localhost:3001)

## Commands

```bash
bun dev          # Start all apps
bun dev:web      # Web only
bun dev:server   # Server only
bun db:push      # Update database
bun db:studio    # Database UI
```

## Deploy

```bash
cd apps/web && bun deploy
```