OpenEnv: AI-Powered Web Perception & Multi-Agent MCP
### 1. Create the File
Run this in your terminal:
```bash
nano README.md
```

### 2. Paste this Content
```markdown
# MCP - Notte Browser Agent 

A high-performance Model Context Protocol (MCP) frontend built with **Next.js**, **Notte SDK**, and **Patchright**. Designed for advanced web perception and AI automation.

## Features
*   **Perception Engine**: Powered by Notte SDK for turning websites into structured data.
*   **Headless Automation**: Uses Patchright (Chromium) with Ubuntu 24.04 compatibility.
*   **Modern UI**: Glassmorphism and minimalist aesthetic.
*   **Vercel Ready**: Optimized for serverless deployment with a full `requirements.txt`.

## Tech Stack
*   **Frontend**: Next.js (TypeScript)
*   **AI Engine**: Notte Agent & SDK
*   **Browser**: Patchright (Chromium)
*   **Environment**: Python 3.12 (Virtual Environment)

## Local Setup

1. **Clone the Repo**:
   ```bash
   git clone [https://github.com/jouzia/MCP.git](https://github.com/jouzia/MCP.git)
   cd MCP/frontend
   ```

2. **Setup Virtual Environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Install Browser Dependencies**:
   ```bash
   patchright install --with-deps chromium
   ```

## Deployment
This project is configured for **Vercel**. Simply connect your GitHub repository and ensure your Environment Variables are set.

---
Built by [Shaik Jouzia Afreen](https://github.com/jouzia) | BCA Student at St. Joseph’s College.
```

---

### 3. Push the Update
After saving the file (`Ctrl+O`, `Enter`, `Ctrl+X`), push it to GitHub using your token:

```bash
git add README.md
git commit -m "docs: add professional README"
git push origin main --force
```
