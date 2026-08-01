# Publishing to the blog

This repo doubles as the source for [MVeng Blog](https://mvaughn51.github.io/mvaughn51/) (Jekyll + Chirpy theme, built from `docs/`).

**Local repo:** `c:\Users\18057\Dropbox\projects\mveng\blog`
**Posts live in:** `docs\_posts\`, named `YYYY-MM-DD-title.md`

## To publish a new post or edit an existing one

1. Add or edit the `.md` file in `docs\_posts\`.
2. Commit and push to `main`:
   ```
   git add docs/_posts/<file>.md
   git commit -m "..."
   git push origin main
   ```
3. `.github/workflows/pages.yml` automatically rebuilds and deploys the site on every push to `main` — no local Jekyll install or manual build step needed. The live site updates within about a minute.

You can check build status under the repo's **Actions** tab if a change doesn't show up.
