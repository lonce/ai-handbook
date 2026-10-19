# Galgo AI Handbook

A living AI learning and practice handbook for Galgo. See `PROJECT_CONTEXT.md` for purpose and evidence conventions, `HANDBOOK_MAP.md` for the provisional topic map, and `AGENTS.md` for contributor guidance.

## Local setup and preview

From the repository root, using PowerShell and Python 3.11 or newer:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\zensical.exe serve
```

If `.venv` is already set up, run just the last command. Open the local URL printed by Zensical (normally `http://localhost:8000/`). Press Ctrl+C to stop the preview.

To generate the HTML website:

```powershell
.\.venv\Scripts\zensical.exe build --strict
```

## Source layout

- `docs/`: Markdown pages included in the website.
- `working/`: drafts and notes excluded from the website. Start new ideas here; move them into `docs/` only at the project owner's direction.
- `site/`: generated HTML; ignored by Git.
- `zensical.toml`: site configuration.
- `requirements.txt`: the pinned Zensical version used for this setup.

The initial landing page is a draft for local review. Building or previewing the site does not publish it. Hosting and access arrangements remain to be decided.

Builder references: [Zensical configuration](https://zensical.org/docs/setup/basics/) and [build usage](https://zensical.org/docs/usage/build/), checked 2026-10-19. The initial configuration was also checked against the locally installed Zensical 0.0.71 template and CLI help.
