# Настройки системы логирования

🧠 Используемая модель: GPT-4-turbo  
📦 Формат: Markdown лог + метаданные JSON  
📅 Цель: управление знанием между сессиями  
📌 Ветка: main, research, architecture, testing

---

## 🤖 ChatGPT Instructions

Follow the `ai-dialog-system` structure and format all outputs using templates from `templates/`.

🧠 Use intents, importance levels, and status from `metadata/tags.json`.  
📄 Format all logs using `dialog_entry_template.md`.  
📌 Continue previous logs if provided, without repeating prior content.  
🗂 Ask for intent and context before starting new threads.  
📘 Use English for commits, filenames, and all documentation.

Keep your answers structured, minimal, and formatted with Markdown where appropriate.
