# AGENTS.md

## Deployment

- GitHub Pages deploys from `main` branch / root (no action workflow).
- The `favicon.ico` is a copy of `logo.png` — update both when changing the logo.

## Local dev

```bash
python3 -m http.server 8080
```

No build step, no package manager, no linter, no tests.

## GitHub Pages path quirk

The site lives under a subpath (`/website/`). The nav logo link `href="/"` navigates to the domain root, not the site root. Use `href="."` or an absolute path with the repo name if that matters.

## License

The repo `LICENSE` is MIT, but the Shamrock project's website content describes it as "Proprietary." These are separate statements — do not treat them as contradictory unless the intent is clarified.
