# .github

## Purpose

Organisation-level GitHub defaults for `thinkei` — PR templates, CODEOWNERS, and shared workflows applied automatically to all repos.

## Repo Structure

```
PULL_REQUEST_TEMPLATE.md  # Default PR template (Jira URL, summary, AI usage disclosure)
CODEOWNERS                # Default code owners for the org
README.md
```

## Architecture Constraints

- Changes here apply **org-wide** — edit with care
- PR template includes mandatory AI usage disclosure checkbox; do not remove it
- No build system or tests — plain Markdown only
