# Replace this folder

This is a placeholder. Delete this file and this folder's contents, then replace them with your own clone of [`nyc-taxi-streamlit-reference`](https://github.com/lassebenni/nyc-taxi-streamlit-reference) on the `chapter-5-start` (or `chapter-5-solution`) branch, with `.git` removed:

```bash
git clone https://github.com/lassebenni/nyc-taxi-streamlit-reference.git /tmp/week11-streamlit
cd /tmp/week11-streamlit
git switch chapter-5-start
rm -rf .git
```

Then copy `/tmp/week11-streamlit/*` (including hidden files like `.env.example`) over this folder. Copy `metric_definitions.template.md` from the repo root into this folder as `metric_definitions.md` and fill it in for every panel you build.

Expected contents once you're done:

```text
week11-streamlit/
├── app.py
├── pyproject.toml
├── uv.lock
├── metric_definitions.md
└── .env            <- credentials, excluded from git
```

See "Building a Metrics Dashboard" (Week 11, Chapter 5) in the curriculum for the full walkthrough.
