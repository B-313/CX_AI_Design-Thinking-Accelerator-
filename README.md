# CX_AI_Design-Thinking-Accelerator-
CX AI Challenge for Pharma Company

# Web Builder

## 🛠️ Agent Pipeline

| Agent | Role | Tools (Free/Local) | Trigger |
|-------|------|--------------------|---------|
| **1: Chatbot** | Assist humans | Local FAQ JS prompts, rule-based feedback (if/then scripts) | Portal Launch |
| **2: Brief Builder** | Form → Structured spec | HTML forms → JSON templates, regex validation | User input |
| **3: Code Generator** | Spec → HTML/CSS | Templated CSS/JS (Pfizer blues: #005EB8 primary), Jinja2 fills | Brief approved |
| **4: Compliance** | Scan code parallel | WCAG: achecker.ca free API or local regex (alt text, ARIA); ABPI: regex for claims/no off-label | Code ready |
| **5: Content QA** | Grammar/links parallel | LanguageTool.org free API; Linkchecker GitHub CLI | Code ready |
