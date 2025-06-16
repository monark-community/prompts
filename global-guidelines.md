# 🌐 Global Prompt Authoring Guidelines

These guidelines apply to all prompt files across this repository. Consistent formatting and structure help AI agents produce better results and make prompts easier for humans to reuse and maintain.

---

## 🧱 File Structure

Every prompt file should follow this consistent format:

```markdown
# 📌 Prompt Title (short and clear)

## 🧠 Context
Briefly describe the scenario and goals. Mention relevant tools, users, or workflows.

## 🛠️ Instructions
What exactly should the agent do? Be clear and directive.

## 📏 Constraints
Mention any limitations (e.g. tech stack, word limits, file structure).

## ✅ Expected Output
Describe the ideal format, tone, or deliverable the agent should return.

## 🔁 Variations (optional)
List ways this prompt could be adapted for other tools, formats, or teams.
```

---

## 🧠 Prompting Best Practices

* Use **simple, direct language**. Avoid jargon unless it’s part of the domain.
* Be **explicit about the audience** or use case (e.g. "for internal docs", "for social media").
* **Break complex tasks into smaller steps**, and guide the agent with structure.
* Prefer **examples over vague instructions**.
* Focus on **what you want**, not how the AI should think.

---

## ✅ Naming Conventions

* Use **kebab-case** for filenames (e.g. `generate-prd.md`, `refactor-component.md`)
* Start with **verbs**: `generate-`, `refactor-`, `optimize-`, `audit-`
* Stay concise and avoid unnecessary nesting

---

## 🔍 Reusability Tips

* Keep prompts **general enough to be reused** across projects, but not so vague they’re useless
* Separate **project-specific details** into clearly marked sections
* When possible, keep **code snippets short** and focus on the intent

---

## 🚫 Avoid

* Overly long context dumps
* Ambiguous instructions like "make it better"
* Mixing multiple unrelated tasks into one prompt
* Hardcoding secrets or credentials

---

Stick to these principles and we’ll build a prompt library that’s both powerful and easy to use across the entire team. 💡
