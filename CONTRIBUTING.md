# Contributing

## Branch & PR Workflow
1. Create a feature branch: `git checkout -b feature/section-name`
2. Make changes (edit `index.html`, add docs/images).
3. Commit: `git commit -m "Add section-name content"`
4. Push: `git push -u origin feature/section-name`
5. Open a Pull Request in GitHub and request a review.

## Content Guidelines
- Keep the homepage concise; link longer artifacts in `/docs`.
- Prefer descriptive filenames (e.g., `docs/poc-data-import.pdf`).
- Keep styles minimal in `css/styles.css`.

## Adding New Sections
Duplicate a `<section>` block in `index.html` and update the `id` and nav link.
