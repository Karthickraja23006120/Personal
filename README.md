# Learning & Work OS 2026–2029

Single-file web app (`index.html`, no build step). Data is stored in the browser (localStorage).

## Host it free on GitHub Pages
1. Create a GitHub repo and upload these files (keep the `.github` folder).
2. Repo Settings → Pages → Source: **GitHub Actions**.
3. Push to `main`. The site appears at `https://<your-username>.github.io/<repo-name>/`.

## Moving your data
localStorage is per site, so data in the Claude page does not carry over. In the old page use Me → Data → Export JSON, then paste it into Import on the new site. Import replaces everything, so keep the export as a backup.

## Making changes
Edit `index.html`, commit, push. Pages redeploys automatically.

## Next step (optional)
Phone alerts while the page is closed need a small backend, for example a Telegram bot run by a scheduled GitHub Action. Keep the bot token in repo Settings → Secrets, never in code.
