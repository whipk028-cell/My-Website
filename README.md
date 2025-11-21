[README.md](https://github.com/user-attachments/files/23666445/README.md)
# Miles Whipkey — Website

This repository contains a static personal website (HTML/CSS/JS). Use GitHub Pages to host it.

How to publish via GitHub (quick):

1. Create a GitHub repository (for example, `whipk028.github.io` or any repo name).
2. Add this repository as the `origin` remote and push:

```bash
# replace <your-github-remote-url> with the HTTPS or SSH URL GitHub gives you
git remote add origin <your-github-remote-url>
git branch -M main
git push -u origin main
```

3. If you want automated deployment to the `gh-pages` branch, keep Actions enabled. This repo contains a workflow that will build/deploy on pushes to `main`.

Notes:
- This project is static. The provided workflow (`.github/workflows/deploy.yml`) publishes the repository contents to the `gh-pages` branch using the built-in `GITHUB_TOKEN` so you don't need to create a PAT.
- If you prefer GitHub Pages served from `main` or `/docs`, you can enable that in the repository Settings → Pages.

If you want, I can create the remote repo for you — you'll need to provide GitHub repo name and grant access (or run the push commands locally).

Enjoy!
