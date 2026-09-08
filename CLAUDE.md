# atiupin.github.io

Personal homepage listing projects hosted on GitHub Pages under
`https://atiupin.github.io/<project>/`.

Static site, no build step. `index.html` is served as-is from the `main` branch root. `styles.css` is the shared global stylesheet, every page links it from the site root (`/styles.css`).

## Commit messages

All messages should be one-liners, ideally not longer than 60 characters. Prefer nouns over verbs. Start with a type prefix: `feat:`, `fix:`, `refactor:`, `test:`, `docs:`, `chore:`. Split unrelated changes to the multiple commits.

## Formatting

Prettier on stock defaults owns all formatting — never hand-format; run `npx --yes prettier --write <files>` after editing any `.html`, `.css`, `.json`, or `.md`.
