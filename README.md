# 📦 AI Project ZIP Generator (Browser-Based)

A **simple browser-based tool** that converts **AI-generated project outputs** (using FILE markers) into a **downloadable ZIP file** — no backend, no server, no setup required.

Perfect for developers who generate projects using AI (ChatGPT, Claude, etc.) and want to quickly download the full project structure.

---

## ✨ Features

- 🧠 Works with AI-generated FILE marker format
- 📁 Automatically creates folder structure
- 📦 Generates ZIP directly in the browser
- 🚫 No backend / No server required
- ⚡ 100% client-side (JSZip + FileSaver)
- 🌐 Can be hosted on GitHub Pages

---

## 📌 Supported AI Output Format

The tool expects AI output in the following format:

```txt
---FILE: src/index.js
<<FILE
console.log("Hello World");
FILE
---END_FILE
