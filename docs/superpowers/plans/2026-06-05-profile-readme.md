# Profile README Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create a dark, moody GitHub profile README for velvetvex that auto-displays on the profile page.

**Architecture:** Single `README.md` file using markdown + minimal HTML for centering. ASCII art header, personal statement, categorized project directory, minimal footer.

**Tech Stack:** Markdown, HTML (alignment only)

---

### Task 1: Create ASCII Art Header

**Files:**
- Create: `README.md`

- [ ] **Step 1: Create README.md with centered ASCII art header**

```markdown
<div align="center">

```
               ___              __                 
 _   _____  / / /  _____  / /_ _   _____  _  __
| | / / _ \/ / / | / / _ \/ __/| | / / _ \| |/_/
| |/ /  __/ /| |/ /  __/ /__ | |/ /  __/>  <  
|___/\___/_/ |___/\___/\__/ |___/\___/_/|_| 
```

</div>
```

Note: The exact ASCII art will be generated at implementation time using a sharp/angular font. The above is illustrative — the implementer should try several options (`ANSI Shadow`, `Bloody`, `Cyberlarge`, `Rectangles`, or similar dark-aesthetic fonts) and pick the best one.

- [ ] **Step 2: Verify render**

Open `README.md` in a markdown previewer or push to GitHub to verify the ASCII art renders correctly inside a code block, centered on the page.

---

### Task 2: Add Personal Statement

**Files:**
- Modify: `README.md`

- [ ] **Step 1: Add personal statement below the header**

Append after the closing `</div>`:

```markdown

<div align="center">

*building things that feel like something.*
*automation, sound, light, code — whatever the medium, the obsession is the same.*

</div>
```

Tone: lowercase, italic, evocative. The implementer may refine the exact wording to match the velvetvex voice — Judy Alvarez energy: intimate, passionate, unapologetic.

---

### Task 3: Add Project Directory

**Files:**
- Modify: `README.md`

- [ ] **Step 1: Add category sections with project listings**

Append after the personal statement:

```markdown

---

### AI & Brainspace

`ai-brainspace` — personal knowledge engine, AI-augmented thinking

### Music & Sound

`ableton-tracker` — learning journal and session tools for Ableton
`rekordbox-tracker` — library management and practice tracking

### Smart Home & Lighting

`ai-apartment` — intelligent lighting automations

### Desktop Automation

`desktop-automations` — workflow scripts and system tools

### Experimental

`hypno-projects` — exploratory work
`kink-projects` — personal creative projects
```

Project names are inline code (backticks) while repos don't exist yet. When a repo goes live, convert to a link: `[repo-name](https://github.com/velvetvex/repo-name)`.

---

### Task 4: Add Footer and Commit

**Files:**
- Modify: `README.md`

- [ ] **Step 1: Add minimal footer**

Append at the bottom:

```markdown

---

<div align="center">

<sub>velvetvex · 2025</sub>

</div>
```

- [ ] **Step 2: Stage and commit**

```bash
git add README.md
git commit -m "feat: add profile README"
```

- [ ] **Step 3: Push to GitHub**

```bash
git push -u origin main
```

- [ ] **Step 4: Verify on GitHub**

Visit https://github.com/velvetvex to confirm the README renders correctly on the profile page.
