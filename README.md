# Publish `index.html` — quick shareable link

This repository contains a static frontend file: [index.html](index.html).

Two quick ways to get a public shareable URL:

1) GitHub Pages (recommended free option)

- Create a GitHub repository (e.g., `my-site`) and push this folder to it.
- From your local folder, run:

```powershell
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

- On GitHub: go to the repository Settings → Pages, set the source to `main` branch and `/ (root)`, then Save. The site will be available at `https://<your-username>.github.io/<repo>/`.

2) Netlify (drag-and-drop or connect GitHub)

- Drag-and-drop this folder in the Netlify Drop UI: https://app.netlify.com/drop
- Or connect your GitHub repo in Netlify and deploy — Netlify will provide a public URL.

Optional helpers and notes

- If you have the GitHub CLI (`gh`), you can create a repo with `gh repo create <repo> --public --source=. --remote=origin --push`.
- If you prefer a quick raw file preview (not ideal for production), you can use the raw file URL via a static CDN such as https://raw.githack.com/ after pushing to GitHub.
- If you want, I can help: initialize a git repo, create the GitHub repo (requires your `gh` auth), or prepare a deploy configuration for Netlify.

Files:

- [index.html](index.html)

Next steps: tell me which hosting option you prefer and I will help prepare or run the necessary commands.
