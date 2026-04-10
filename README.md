# Factory QC Environmental Logger — Technical Assessment

## Overview

Welcome to the full-stack technical assessment. You have **2 hours** to build a working prototype of an **Ambient Conditions Logger** for a plastics manufacturing Quality Control (QC) team.

Please read the full assessment brief in **[ASSESSMENT.md](ASSESSMENT.md)** before you begin.

## Pre-configured Stack

This repository comes pre-configured with everything you need:

- **Laravel 13** with PHP 8.4
- **React 19** with TypeScript
- **Inertia.js v3** (React adapter)
- **Tailwind CSS v4**
- **Pest v4** for testing
- **SQLite** database (pre-configured)
- **Laravel Breeze** authentication scaffolding

## Getting Started

### Prerequisites

- PHP 8.4+
- Composer
- Node.js 20+
- npm

### Setup

1. **Fork this repository** to your own GitHub account, then clone your fork:

   ```bash
   git clone <your-fork-url>
   cd assessment
   ```

2. **Run the setup script:**

   ```bash
   composer setup
   ```

   This will install PHP and Node dependencies, generate an app key, run migrations, and build frontend assets.

3. **Start the development servers:**

   In one terminal:
   ```bash
   php artisan serve
   ```

   In another terminal:
   ```bash
   npm run dev
   ```

4. **Open your browser** at [http://localhost:8000](http://localhost:8000)

### Running Tests

```bash
php artisan test --compact
```

To run a specific test file:
```bash
php artisan test --compact --filter=YourTestName
```

### Code Formatting

After modifying PHP files, run Pint to auto-format:
```bash
vendor/bin/pint --dirty
```

## What To Do Next

1. Read **[ASSESSMENT.md](ASSESSMENT.md)** for the full project brief and task breakdown.
2. Create a **THOUGHTS.md** file in the root directory to document your process (see the assessment brief for details).
3. Start coding — and commit frequently so we can see your workflow.

## AI Coding Tools

You are **encouraged** to use AI-assisted coding tools (GitHub Copilot, Cursor, Claude Code, ChatGPT, etc.) during this assessment. We want to see how you leverage these tools effectively as part of a modern development workflow.

Document your AI tool usage in your THOUGHTS.md file.

Good luck!
