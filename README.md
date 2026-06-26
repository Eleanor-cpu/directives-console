# directives-console
A high-performance, local-first task console for power users. Built with Vanilla JS and IndexedDB, it offers a keyboard-first workflow, fluid animations, and robust data sovereignty. No accounts, no cloud—just your directives. Featuring ⌘K focus, intuitive nav, and JSON export/import.
Key Features
​Keyboard-First Workflow: Navigate, toggle, delete, and edit tasks entirely from your keyboard (⌘/Ctrl+K to focus).
​Local-First Persistence: Data is stored directly on your machine using IndexedDB (with localStorage fallback) to ensure zero data leakage and high capacity.
​Portable: Built-in JSON Export/Import functionality for easy backups and device migration.
​Optimized UX: Features include task sorting (Date vs. Status), animated removal, toast notifications, and zero-latency UI updates.
​How to use
​Deploy: This repository is pre-configured for GitHub Pages.
​Access: Open the live link to begin logging your directives.
​Shortcuts:
​⌘/Ctrl + K: Focus the input box.
​Arrow Keys: Navigate through your task list.
​Space: Toggle completion status.
​Delete/Backspace: Remove a task.
​Enter: Edit a task.
​Tech Stack
​Language: Vanilla JavaScript (ES6+)
​Styling: CSS3 (Custom properties, backdrop-filters, keyframe animations)
​Storage: IndexedDB / localStorage
​Markup: Semantic HTML5
