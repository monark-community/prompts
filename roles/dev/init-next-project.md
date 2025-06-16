# Initialize Next Project

This project uses the latest Next.js 15 features and best practices. Please base all code on a project scaffolded with the following command:

```bash
npx create-next-app@latest [project-name] --yes
```

This sets up the project with TypeScript, ESLint, Tailwind CSS, and App Router—all of which are required.

## 🔧 Tech Stack

- Framework: Next.js 15 (App Router)
- Language: TypeScript
- Styling: Tailwind CSS
- UI Library: shadcn/ui
- Architecture: SaaS-oriented
- Linting: ESLint
- Secrets: All sensitive data must go in .env files and be accessed via process.env

## Guidelines

- ✅ Use Tailwind utility classes for styling
- ✅ Use shadcn/ui for UI components
- ✅ Store all secrets and configs in .env (never hardcode)
- ✅ Structure files clearly: app/, components/, lib/, hooks/, etc.
- ✅ Code should be clean, readable, and pass ESLint checks
- ✅ Default to accessibility and responsiveness

## Do Not

- ❌ Use JavaScript (TypeScript only)
- ❌ Use pages/ directory or old Next.js patterns
- ❌ Use CSS modules, SCSS, or styled-components
- ❌ Use generic UI kits like Bootstrap or MUI
- ❌ Hardcode any environment-specific values