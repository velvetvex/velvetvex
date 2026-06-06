# Profile README Design Spec

## Overview

GitHub profile README for `velvetvex/velvetvex` — auto-displayed on the velvetvex GitHub profile page.

## Aesthetic

- Judy Alvarez (Cyberpunk 2077) inspired: dark, moody, intimate, passionate
- Tattoo-culture energy, neon in shadow
- Unapologetically personal

## Structure

### 1. ASCII Art Header

- Stylized "velvetvex" in a dark/angular font
- Centered via HTML `<div align="center">`
- No bubbly or playful fonts — sharp, moody

### 2. Personal Statement

- 1-2 lines, lowercase, italic
- Manifesto fragment, not a bio
- Evocative, first-person
- Example tone: "building things that feel like something. automation, sound, light, code — whatever the medium, the obsession is the same."

### 3. Project Directory

Categories with projects listed under each. Each project gets a one-liner description. Repos that don't exist yet shown as plain text; swapped to live links when created.

Categories:
- **AI & Brainspace** — personal knowledge engine, AI-augmented thinking
- **Music & Sound** — Ableton learning/session tools, Rekordbox library/practice tracking
- **Smart Home & Lighting** — intelligent lighting automations
- **Desktop Automation** — workflow scripts and system tools
- **Experimental** — hypno projects, kink projects, personal creative work

Format: scannable, no description longer than one line per project.

### 4. Footer

- Minimal single line
- `velvetvex © 2025` or a moody one-liner closer
- No social links, badges, or stats widgets

## Technical Details

- Pure markdown with minor HTML for centering
- No external dependencies or hosted images
- Single file: `README.md`
