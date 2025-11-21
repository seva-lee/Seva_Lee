# Pokémon Collection (static site)

This is a single-file static site at `index.html` that lists Pokémon and shows detail pages using the PokéAPI.

Ways to publish so Google (and others) can find it:

1) Publish via GitHub Pages (recommended)

- Install Git for Windows: https://git-scm.com/download/win
- Create a GitHub repo (via website) and follow the PowerShell commands below to push.
- In GitHub repository Settings → Pages, set branch to `main` (root) and save. Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

PowerShell example (run from `C:\program`):

```powershell
# check git
git --version

# initialize repo and push (run after creating an empty repo on GitHub)
git init
git add .
git commit -m "Initial site"
git branch -M main
# replace the URL below with the repo URL from GitHub
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

2) Netlify (very quick)

- Go to https://app.netlify.com/drop and drag the site folder (or just `index.html`) to publish. Netlify provides a public URL immediately and can be connected to GitHub for continuous deploys.

3) Google Drive (storage only)

- Google Drive is for file storage, not proper website hosting. You can upload the file to Drive to share, but it won't be a searchable public website like GitHub Pages.

If you'd like, I can:
- create a `.gitignore` (done),
- run git commands here if Git is installed on your machine, or
- prepare a GitHub repo description and PR-ready package for you to push.

Tell me which option you want me to continue with and I will provide the exact next commands.
