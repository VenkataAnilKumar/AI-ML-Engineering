# Contributing Guidelines

Thanks for considering a contribution! This repository curates free learning resources for AI/ML. Please follow these guidelines to keep the list high-quality, visual, and easy to navigate.

## What qualifies

- Free to access resources: MOOCs, tutorials, books/PDFs, blogs, videos, guides, datasets.
- Open-source libraries/tools (OSI-approved licenses preferred) and official docs.

Not accepted:
- Paywalled/trialed content, affiliate links, self-promotional spam, or pirated copies.

## Submission checklist

- The resource is free to access (no paywall/trial). If audit-only, note it.
- Libraries/tools are open-source and link to official repo/docs.
- Provide a concise summary (1 short sentence).
- Use the table format and include Type icon, Difficulty, and Last Checked date.
- Place the link in the appropriate section table (keep alphabetical order by Name where possible).
- Avoid duplicates; search the repo first. Prefer canonical/original links.

## Table format

Please add entries as a table row with these columns:

| Name | Type | Difficulty | Link | Summary | Last Checked |
|---|---|---|---|---|---|

- Type icons: 📘 Book · 🎥 Video · 📝 Tutorial · 🧑‍🏫 Course · 📚 Docs · 📰 Blog · 📄 Paper · 🗂️ Dataset · 🔧 Tool
- Difficulty tags: Beginner · Intermediate · Advanced
- Last Checked: YYYY-MM-DD (verify the link is accessible and free on that date)

For Case Studies specifically, use the same table format under the appropriate subsection (Industry & Product, MLOps & Platforms, Responsible AI, Competition) or under a relevant domain in the "By Domain" section (e.g., Recommenders, Search & Ranking, Fraud & Risk, Ads & Marketing, Transportation & Logistics, Healthcare, Maps/Geospatial, NLP & Content, Finance & FinTech, Security & Privacy). Prefer canonical company domains over Medium when available. For longer write-ups, add a separate markdown following `7-Case-Studies/TEMPLATE.md` and link it from the table.

### Recently updated marker (optional)

Append 🆕 to the Name for entries added or updated within the last 30 days.

## Where to add

- `1-Foundations/README.md` — Math, Probability & Statistics, DSA/Algorithms
- `2-Machine-Learning/README.md` — Supervised, Unsupervised, Reinforcement Learning
- `3-Deep-Learning/README.md` — NN basics, CNNs, RNNs, Transformers
- `4-Tools-Libraries/README.md` — Python, NumPy, Pandas, TF, PyTorch, scikit-learn, JAX, etc.
- `5-Practical-Projects/README.md` — Pipelines, Kaggle starters, datasets, real-world guides
- `6-Free-Books-Courses-Blogs/README.md` — Curated list of free books, courses, and blogs
- `7-Case-Studies/README.md` — Real-world ML case studies (engineering blogs, user stories, platform write-ups). Use `7-Case-Studies/TEMPLATE.md` for structured summaries (optional).

## Top 5 recommendations

Each section highlights a "Top 5" list. You may propose updates to the Top 5 in your PR, with a short rationale (quality, breadth, recency, accessibility).

## Changelog

Maintainers will update `CHANGELOG.md` after merging. You may include a brief entry suggestion in your PR description.

## How to contribute

1. Fork the repo and create a branch for your change.
2. Edit the appropriate `README.md` and add your entry as a table row.
3. Ensure alphabetical order within the table by Name where possible.
4. Open a Pull Request with a short description, confirming the resource is free and accessible on the Last Checked date.

Thank you for helping the community learn AI/ML for free!
