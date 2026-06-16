# Setup Development Environment — Summary

This document summarizes the steps I completed to fulfill the development environment setup instructions and GitHub repository requirements.

---

## Tools Installed

| Tool | Purpose |
|------|---------|
| **Cursor IDE** | AI-powered code editor for writing and editing code locally |
| **Claude Code** (Cursor plugin) | AI assistant add-on in Cursor for coding help |
| **Codex** (Cursor plugin) | Additional AI assistant add-on in Cursor |
| **Git** | Version control system for managing file changes and syncing with GitHub |

In addition to the required steps above, I also learned about **Agent Composer** in Cursor IDE — an AI agent feature that helps complete coding tasks interactively (e.g., editing files, running commands, and explaining each step).

---

## Steps Completed

### 1. Install Cursor IDE
- Downloaded and installed Cursor from [https://cursor.com/](https://cursor.com/)
- Opened Cursor as the main editor for repository work

### 2. Install & Log In to Claude Code
- Opened **Extensions** in Cursor
- Searched for **"Claude Code"**, installed the add-on, and logged in to the required account

### 3. Install & Log In to Codex
- Opened **Extensions** in Cursor
- Searched for **"Codex"**, installed the add-on, and logged in to the required account

### 4. Create a Public GitHub Repository
- Created a GitHub account (if not already available) at [https://github.com/](https://github.com/)
- Created a **public** repository to store the project

### 5. Open the Repository in Cursor
- Opened the GitHub repository in Cursor IDE to edit files locally

### 6. Create / Edit README.md
- Used Cursor (including Agent Composer) to update `README.md` according to the project needs
- This repository contains a CV in Markdown format in `README.md`

### 7. Commit & Push to GitHub
- Saved changes using Git (`git add`, `git commit`, `git push`) so they are available on GitHub

### 8. README Link on GitHub
- After pushing, `README.md` can be accessed directly from the repository page on GitHub

---

## Issues Encountered & How I Solved Them

### Issue: Git was not installed on my laptop

**Context:** I do not have an IT background, so I was initially unfamiliar with Git and other development tools. When I tried to follow the instructions (clone repository, commit, push), Git commands did not work because Git was not installed on my system.

**What I did:**
1. Learned the basics of **what Git is** — a tool for tracking file changes and collaborating through platforms like GitHub
2. Studied **how to install Git on Windows** (download the official installer, follow the installation wizard, verify with `git --version` in the terminal)
3. After Git was installed, used the **`git clone`** command to copy the repository from GitHub to my laptop, then opened it in Cursor IDE to edit `README.md`

**Outcome:** Git was successfully installed and I was able to continue the workflow: clone → edit in Cursor → commit → push to GitHub.

**Takeaway:** Even without an IT background, I can still learn new tools by reading documentation, trying step by step, and using AI assistants (Cursor, Claude Code, Codex, Agent Composer) when I get stuck.

---

## Summary

I completed all required steps (install Cursor, Claude Code & Codex plugins, create a GitHub repo, open in Cursor, README, commit & push). The main obstacle was installing Git; once I understood it and installed it, the workflow from clone to push ran smoothly.
