# Second Brain Starter (Obsidian)

Build a second brain your AI can read. Works with Claude, ChatGPT, Codex, Cursor, or any agent.

This README is the single instruction file for humans and AI. Point your agent here.

Starter repo: https://github.com/reecehardin/second-brain-demo

---

## Why the vault already “knows” GitHub

When you download or clone this project, you are not getting loose notes only. You are getting a **git repository**.

Inside the folder is a hidden `.git` directory. That is what stores:
- version history
- the link to GitHub (`origin`)

Obsidian does **not** magically find your GitHub.  
**Obsidian Git** just uses the git repo that already came with the folder.

If you use **Use this template** on GitHub, your new repo starts with that same git link pointed at **your** copy.

---

## Full setup from zero (beginner path)

Do these in order. No prior coding required.

### Step 1. Install Obsidian
1. Go to https://obsidian.md
2. Download for Mac or Windows
3. Install and open it
4. You can skip creating a vault for now

### Step 2. Create a GitHub account
1. Go to https://github.com and sign up / log in
2. This is where your brain will sync

### Step 3. Install GitHub Desktop (easiest auth)
This avoids Terminal commands like `gh auth login`.

1. Download **GitHub Desktop**: https://desktop.github.com
2. Install it
3. Sign in with your GitHub account
4. That signs git on your computer the friendly way

Optional advanced path: install Git + GitHub CLI and run `gh auth login`. Most people should use GitHub Desktop.

### Step 4. Get YOUR copy of this starter
On https://github.com/reecehardin/second-brain-demo

1. Click **Use this template** → **Create a new repository**
2. Name it something like `second-brain`
3. Choose **Private** unless you want it public
4. Create it

Then open GitHub Desktop:
1. **File → Clone repository**
2. Pick your new `second-brain` repo
3. Choose a simple local folder (example: `Documents/second-brain`)
4. Clone

You now have the vault files on your computer, already linked to **your** GitHub repo.

### Step 5. Open it in Obsidian
1. Open Obsidian
2. **Open folder as vault**
3. Select the folder you just cloned (`Documents/second-brain`)
4. Trust the vault if asked

### Step 6. Turn on auto sync every 10 minutes
1. In Obsidian: Settings → **Community plugins**
2. Turn **Safe mode** off
3. Browse → search **Obsidian Git** → Install → Enable
4. Open Obsidian Git settings → **Automatic**
5. Set **Auto commit-and-sync interval (minutes)** to `10`
6. Leave **Split timers** off
7. Optional: turn on **Auto commit-and-sync after stopping file edits**

That is the sync. Obsidian Git commits and pushes to the GitHub remote that already came with the cloned folder.

### Step 7. Give the brain an identity
Edit these three files in `_identity/`:
1. `user.md` — who you are
2. `soul.md` — how the AI should act
3. `identity.md` — who the AI is

Pro tip: ask any AI to interview you, then draft those three files.

### Step 8. Start capturing
- Put new notes in `00_inbox/` first
- One idea per file
- Link people/projects with `[[wikilinks]]`
- Never put passwords, API keys, or card numbers in the vault

### Step 9. Let AI clean it up (any model)
Point your AI at this README and ask it to run the **Filing / cleanup** section below on a schedule or at the end of the day.

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
| `maps/` | Optional maps of content when a topic gets messy |
| `_identity/` | Who you are, how AI should act, who the AI is |
| `workflows/` | Repeatable playbooks |

## House rules
- New facts go to `00_inbox/` first
- One idea per file
- Use `[[wikilinks]]`
- No secrets in the vault
- GitHub is the source of truth across Mac / Windows / agents

---

## Instructions for AI agents

Read this whole README before editing the vault.

### Before substantive work
1. Read `_identity/user.md`, `_identity/soul.md`, and `_identity/identity.md` if they exist
2. Pull latest from git if you can
3. Prefer updating existing notes over creating duplicates

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
6. Commit and push with a clear message like `vault cleanup: YYYY-MM-DD`

### Hard constraints
- Do not invent facts
- Do not delete notes you are unsure about
- Do not store secrets
- Do not dump raw data. Synthesize and link.

### Nightly compounding
Run the **Filing / cleanup** section on a schedule with whatever AI tool you use. Manual end-of-day is fine too.

---

## Free checklist
https://reecehardin.com/checklist

More on this setup: https://reecehardin.com/brain
