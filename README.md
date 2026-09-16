# Second Brain Starter (Obsidian)

Clone this, open it in Obsidian, turn on Git sync, and you have a second brain your AI can use.

This is the starter vault from Reece Hardin's tutorial on building an Obsidian second brain with GitHub auto-sync and a nightly AI cleanup job.

## Quick start

### 1. Get your own copy
**Easiest:** on GitHub click **Use this template** → create a new repo under your account (private is fine).

**Or clone:**
```bash
git clone https://github.com/reecehardin/second-brain-demo.git
cd second-brain-demo
```

If you cloned my repo directly, create your own GitHub repo and change the remote so you are not pushing to mine:
```bash
gh repo create YOUR_USERNAME/second-brain --private --source=. --remote=origin --push
```

### 2. Open in Obsidian
1. Open Obsidian
2. **Open folder as vault**
3. Select this folder

### 3. Turn on auto sync (about every 10 minutes)
1. Settings → Community plugins → turn off Safe mode
2. Browse → install **Obsidian Git** → Enable
3. Obsidian Git settings:
   - Auto commit after every change (or on interval)
   - Auto push interval: **10** minutes (or close)
   - Pull on startup / periodic pull: on

Now Mac, Windows, or any clone of this repo stays on the same brain.

### 4. Capture during the day
- New notes go in `00_inbox/` first
- One idea per file
- Link people and projects with `[[wikilinks]]`
- Never put passwords, API keys, or card numbers in the vault

### 5. Nightly AI cleanup
Open `nightly-job.md` and run that prompt on a schedule with Claude Code, Cursor, or any agent that can edit this repo.

It should:
1. Pull latest
2. File `00_inbox/` into the right folders
3. Create stubs + strengthen `[[wikilinks]]`
4. Write a short review note
5. Commit and push

## Folder map

| Folder | What goes here |
|---|---|
| `00_inbox/` | Raw captures. Unprocessed. |
| `people/` | One note per person |
| `projects/` | One note per project |
| `decisions/` | Locked decisions |
| `knowledge/` | Reusable how-tos |
| `_identity/` | Who you are (for AI) |
| `workflows/` | Repeatable playbooks |

Also included:
- `CLAUDE.md` — rules for AI working in this vault
- `nightly-job.md` — the nightly compounding prompt

## Tips
- Start messy. Capture first. File later (or let the nightly job file for you).
- GitHub `main` is the source of truth.
- The vault is memory, not a chat room.

## Free checklist
More practical AI setup: [reecehardin.com/checklist](https://reecehardin.com/checklist)

---
Built for the YouTube tutorial. Fork it. Make it yours.
