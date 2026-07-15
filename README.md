# SkillATS help centre

User-facing help for **SkillATS** ([skillats.com](https://skillats.com)) — written for recruiters and hiring teams.

Built with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Run locally (docs editors)

```bash
cd skill-ats
python3 -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
mkdocs serve
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Edit the help content

1. Change Markdown under `docs/`.
2. Add new pages to `nav:` in `mkdocs.yml`.
3. Add screenshots to `docs/assets/` — see `docs/reference/Screenshots_checklist.md` (editor-only; not in the public menu).
4. Preview with `mkdocs serve`, then commit and push.

Write for **end users**: menu names, buttons, and steps — not URLs, APIs, or code.

## Build & deploy

```bash
mkdocs build
```

GitHub Pages: workflow in `.github/workflows/deploy.yml`. Or run `mkdocs gh-deploy`.
