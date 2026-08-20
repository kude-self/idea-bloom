# IdeaBloom

Interactive prototype for turning a rough idea into a creation blueprint and an AI-ready build prompt.

## Live URL

https://kude-self.github.io/idea-bloom/

## Current flow

1. Enter a rough idea.
2. Expand it into key needs.
3. Choose creation depth.
4. Answer one context-sensitive follow-up question.
5. Generate a creation blueprint, first-version scope, future path, and a copyable AI build prompt.

## Deployment

- Repository: public
- Branch: `main`
- Static entry file: `index.html`
- `.nojekyll` included
- GitHub Pages deployment workflow: `.github/workflows/pages.yml`
- Smoke-test workflow: `.github/workflows/test.yml`

## Smoke tests

The automated smoke test checks:

- `index.html` exists
- essential interaction buttons exist
- viewport/mobile markers exist
- inline JavaScript passes `node --check`
- mobile font size / responsive CSS markers exist

## Manual mobile test checklist

- Open in Safari on iPhone
- Enter a sample idea
- Tap `幫我展開這個想法`
- Verify idea map appears and scrolls into view
- Switch creation depth
- Tap `就是這個方向`
- Answer the follow-up question
- Generate the creation blueprint
- Verify prompt is produced
- Tap copy and paste into Notes to confirm clipboard output
- Test at small and large text sizes
