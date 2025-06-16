# Initialize Next Project

Let's create a new Next.js project named {{project_name}} following the standard Monark structure.

1. Run the project initialization command;

```bash
npx create-next-app@latest [project-name] --yes
```

This sets up the project with TypeScript, ESLint, Tailwind CSS, and App Router—all of which are required.

2. Install SASS

```bash
npm i sass
```

3. Initialize shadcn-ui and install some common components.

```bash
npx shadcn@latest init
npx shadcn@latest add button
npx shadcn@latest add card
npx shadcn@latest add input
``` 

4. Copy the official Monark shadcn-ui theme from https://github.com/monark-community/website/blob/main/app/globals.scss

5. Create `.env.example` and `.env` files with an example config
