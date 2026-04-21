# haulercompile

Renewal tracking SaaS for small trucking businesses.

## Overview
haulercompile is a SaaS project for small trucking businesses in the U.S. to prevent missed renewals for insurance, UCR, permits, and truck or driver documents.

## Planned Tech Stack
- Next.js
- TypeScript
- Supabase
- Tailwind CSS
- shadcn/ui
- Zod
- Resend (later)

## Repository Structure
```text
haulercompile/
├─ README.md
├─ .gitignore
├─ .env.example
├─ docs/
│  ├─ requirements.md
│  └─ architecture.md
├─ app/
│  ├─ frontend/
│  └─ backend/
└─ infra/
```

## Getting Started
At the moment, this repository contains the initial project structure. The exact startup commands will be finalized after the frontend app is scaffolded.

### Prerequisites
- Git
- Node.js 20 or later
- npm 10 or later

### 1. Clone the repository
```bash
git clone https://github.com/Luke-2164/haulercompile.git
cd haulercompile
```

### 2. Set environment variables
Create a local environment file from the example file.

```bash
cp .env.example .env.local
```

On Windows PowerShell, use:

```powershell
Copy-Item .env.example .env.local
```

Then fill in the required values in `.env.local`.

### 3. Install dependencies
After the frontend app is created under `app/frontend`, run:

```bash
cd app/frontend
npm install
```

### 4. Start the development server
After the frontend app is scaffolded, run:

```bash
npm run dev
```

## Current Status
- Repository initialized
- Initial folder structure created
- Requirements and architecture docs added
- Frontend app not scaffolded yet

## Notes
The Getting Started section is intentionally written as an initial draft. It will be updated once the Next.js app and actual scripts are added.
