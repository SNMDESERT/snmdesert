# SNMDESERT GitHub Profile

## Install

1. Create a **public** GitHub repository named exactly `SNMDESERT` under the account `SNMDESERT`.
2. Add `README.md` from this package to the repository root.
3. Add `.github/workflows/snake.yml` at the exact path shown.
4. Commit and push the files to the default branch (usually `main`).
5. Open the repository's **Actions** tab. If prompted, enable Actions.
6. Select **Generate contribution snake** → **Run workflow**. Wait for it to finish.
7. The workflow creates/updates the `output` branch. The snake image should then load in the README.

## Customize before publishing

- In `README.md`, replace the SNMAC placeholder repository URL and the exam-results project placeholder with your real repository links.
- Remove or adjust any project description that doesn't match what you have published.
- Add a contact link only if you want it public.
- The language card reflects public repository contents, not your personal skill level.
- Animated banners and statistics use third-party services, so they may occasionally be unavailable or rate-limited.

## If the snake does not appear

- Check **Settings → Actions → General** and ensure workflows are allowed.
- Ensure the workflow has read/write repository permissions if organization policy permits it.
- Run the workflow manually again and inspect the Actions logs.
- Confirm that the `output` branch contains `github-contribution-grid-snake.svg` and `github-contribution-grid-snake-dark.svg`.

## Files

- `README.md` — profile layout, animated banner, tech stack, projects, stats and three-language bio.
- `.github/workflows/snake.yml` — automatically generates and publishes the contribution snake SVGs.
