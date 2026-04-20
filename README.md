# Thought Spores

Interactive idea-mapping canvas where prompts bloom into floating thought nodes.

## Run locally

Open [index.html](index.html) in a browser.

## Deploy to GitHub Pages

This repo includes an Actions workflow that deploys the static site automatically.

1. Push this repository to GitHub (branch: `main`).
2. In GitHub, open Settings -> Pages.
3. Under Build and deployment, set Source to GitHub Actions.
4. Push any new commit to `main`.
5. Wait for the workflow named Deploy static content to Pages to finish.

Your site URL will be:

https://<your-github-username>.github.io/llm_diagram_rob/

## Project files

- [index.html](index.html): App UI, styles, and logic.
- [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml): GitHub Pages deployment workflow.