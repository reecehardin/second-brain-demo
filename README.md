# Second Brain Starter (Obsidian)

A simple local second brain for you and your AI.

No GitHub required. No syncing setup. Just Obsidian on your computer.

Starter: https://github.com/reecehardin/second-brain-demo

This README is the single instruction file for humans and any AI agent (Claude, ChatGPT, Codex, Cursor, etc.).

---

## Quick start (beginner)

### 1. Install Obsidian
1. Go to https://obsidian.md
2. Download for Mac or Windows
3. Install and open it

### 2. Get this starter onto your computer
Easiest options:

**Option A. Download ZIP**
1. Open https://github.com/reecehardin/second-brain-demo
2. Click the green **Code** button → **Download ZIP**
3. Unzip it somewhere easy (example: Documents/second-brain)

**Option B. Use this template** (optional, only if you already use GitHub)
1. Click **Use this template**
2. Create your own repo
3. Download or clone it

Most people should use **Option A**.

### 3. Open it as a vault
1. In Obsidian click **Open folder as vault**
2. Select the unzipped folder
3. Trust the vault if asked

### 4. Give the brain an identity
Edit these three files in `_identity/`:
1. `user.md` — who you are
2. `soul.md` — how the AI should act
3. `identity.md` — who the AI is

Pro tip: ask any AI to interview you, then draft those three files for you.

### 5. Start capturing
- Put new notes in `00_inbox/` first
- One idea per file
- Link people and projects with `[[wikilinks]]`
- Never put passwords, API keys, or card numbers in the vault

### 6. Let AI help clean it up
Point your AI at this README and ask it to run the **Filing / cleanup** section below.

---

## Folder map

| Folder | What goes here |
|---|---|
| `00_inbox/` | Raw captures. Unprocessed. One idea per file. |
| `people/` | One note per person |
| `projects/` | One note per project |
| `decisions/` | Locked decisions |
| `companies/` | Companies, competitors, vendors |
| `meetings/` | Meeting notes |
| `daily/` | Short daily dumps |
| `knowledge/` | Reusable how-tos, frameworks, quotes |
| `maps/` | Optional maps when a topic gets messy |
| `_identity/` | Who you are, how AI should act, who the AI is |
| `workflows/` | Repeatable playbooks |

## House rules
- New facts go to `00_inbox/` first
- One idea per file
- Use `[[wikilinks]]`
- No secrets in the vault
- Keep it local and simple

---

## Instructions for AI agents

Read this whole README before editing the vault.

### Before substantive work
1. Read `_identity/user.md`, `_identity/soul.md`, and `_identity/identity.md` if they exist
2. Prefer updating existing notes over creating duplicates

### When capturing new information
- Write new raw facts to `00_inbox/` as `YYYY-MM-DD-slug.md`
- One idea per file
- Use `[[wikilinks]]`

### Filing / cleanup
1. Process everything in `00_inbox/` into the right folders
2. Create stub notes for missing people / projects / companies
3. Convert plain mentions into `[[wikilinks]]`
4. Merge only obvious duplicates. If unsure, leave in `00_inbox/`
5. Optionally write a short review note in `daily/`

### Hard constraints
- Do not invent facts
- Do not delete notes you are unsure about
- Do not store secrets
- Do not dump raw data. Synthesize and link.

### Optional later upgrades
Multi-device GitHub sync and nightly scheduled cleanup are optional advanced upgrades. This starter is designed to work fully offline on one computer first.

---

## Free checklist
https://reecehardin.com/checklist

More on this setup: https://reecehardin.com/brain
