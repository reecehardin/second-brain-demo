# Second Brain Starter (Obsidian)

Public starter vault from Reece Hardin's tutorial.

**Easiest path:** click **Use this template** → create YOUR repo → open the folder in Obsidian → turn on Obsidian Git → fill `_identity/` → capture into `00_inbox/`.

Repo: https://github.com/reecehardin/second-brain-demo

This README is the single source of instructions for humans and for any AI agent (Claude, ChatGPT, Codex, Cursor, etc.). Point your agent at this file.

## Quick start (humans)

1. On GitHub click **Use this template** and create a repo under your account (private is fine).
2. Clone it to your computer.
3. Open Obsidian → **Open folder as vault** → select this folder.
4. Install the **Obsidian Git** community plugin.
5. Turn on auto commit + auto push about every **10 minutes**, and pull on startup.
6. Edit the three files in `_identity/` (or have an AI interview you and draft them).
7. Put new notes in `00_inbox/` first.

Do not push to Reece's repo. Make it yours first.

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
- Link with `[[wikilinks]]` when you mention a person, project, or company
- Never store passwords, API keys, or card numbers
- GitHub `main` is the source of truth across devices
- This vault is memory, not a chat room

## Identity files

In `_identity/`:

1. `user.md` — who the human is, role, communication style, frameworks
2. `soul.md` — how the AI should act (tone, values, constraints)
3. `identity.md` — who the AI is (name, role mix)

Pro tip: have any AI interview you, then draft these three files.

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
- Use `[[wikilinks]]` to people, projects, and companies

### When filing / cleaning the vault
1. Process everything in `00_inbox/` into the right folders (`people/`, `projects/`, `decisions/`, `companies/`, `meetings/`, `knowledge/`)
2. Create stub notes for people, projects, or companies that were mentioned but missing
3. Convert plain mentions into `[[wikilinks]]`
4. Merge only obvious duplicates. If unsure, leave the note in `00_inbox/`
5. Optionally write a short review note in `daily/` with what needs human attention
6. Commit and push with a clear message like `vault cleanup: YYYY-MM-DD`

### Hard constraints
- Do not invent facts
- Do not delete notes you are unsure about
- Do not store secrets in the vault
- Do not bloat notes with raw dumps. Synthesize and link.

### Nightly compounding (optional schedule)
Any AI tool that can edit this repo can run the "When filing / cleaning the vault" section on a schedule (nightly is ideal). Manual is fine too: paste that section to your agent at the end of the day.

---

## Free checklist

Practical AI setup: https://reecehardin.com/checklist

More on the brain setup: https://reecehardin.com/brain
