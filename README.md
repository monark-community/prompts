# 🧠 AI Prompts Repository

This repository contains curated, reusable prompts to guide AI agents (Claude, ChatGPT, Lovable, etc.) in accomplishing tasks across development, design, product, and operations.

Our goal is to:

* Standardize how we interact with AI tools
* Improve output quality through clear instructions
* Empower teams to automate and accelerate common tasks

---

## 📆 Repository Structure

```
prompts/
├── doc/                  # Documentation for different AI agents setup & best practices
├── roles/                # Prompts by roles
   ├── dev/                  # Developer workflows: scaffolding, refactoring, testing
   ├── design/               # Design support: UX audits, Figma naming, accessibility
   ├── marketing/            # Marketing assets: ad copy, emails, positioning, SEO
   └── product/              # Product management: PRDs, user stories, ticket generation
├── global-guidelines.md  # Prompt authoring best practices
└── README.md             # This file
```

---

## 💪 How to Use

1. Browse the folders relevant to your role or task.
2. Copy the appropriate prompt into your AI tool (Claude, ChatGPT, etc.).
3. Adjust any context-specific details as needed.
4. Use the AI output as a draft and review before using it in production.

---

## ✅ Prompt Format Guidelines

All prompts should follow this structure:

* **Context**: Brief description of the task and intended agent.
* **Instructions**: Clear and direct request for the agent.
* **Constraints**: Any technical or formatting limitations.
* **Expected Output**: Ideal structure or result.

Use Markdown for formatting. Avoid long context dumps. Keep it focused and reusable.

---

## 📖 Examples

* `roles/dev/frontend-scaffold.md`: Start a Next.js 15 + Tailwind + shadcn/ui SaaS app
* `roles/design/ux-audit.md`: Ask an agent to review a layout for usability
* `roles/product/prd-generator.md`: Generate a PRD from a user need statement

---

## 🚫 What Not To Do

* Don’t hardcode secrets or credentials in example prompts
* Don’t create tool-specific prompts without naming the tool
* Don’t duplicate prompts across folders

---

## 🚀 Contributing

We welcome new prompt additions!

* Follow the structure above
* Use pull requests and add a short summary of what your prompt does

---

Let’s build smarter workflows together – one prompt at a time. ✨
