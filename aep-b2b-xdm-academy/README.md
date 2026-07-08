# AEP Academy: B2B XDM Relationship Builder

Static single-page educational game for learning Adobe Experience Platform B2B XDM relationships.

## GitHub Pages

Expected Pages URL after publishing:

```text
https://scott-Gresack.github.io/aep-b2b-xdm-academy/
```

## Deploy

Create an empty GitHub repository named `aep-b2b-xdm-academy`, then push this folder:

```bash
cd /Users/gresack/test/aep-b2b-xdm-academy
git init
git add .
git commit -m "Publish AEP Academy"
git branch -M main
git remote add origin https://github.com/scott-Gresack/aep-b2b-xdm-academy.git
git push -u origin main
```

Then enable GitHub Pages:

1. Open the repo in GitHub.
2. Go to `Settings` -> `Pages`.
3. Source: `Deploy from a branch`.
4. Branch: `main`.
5. Folder: `/root`.
6. Save.

The app is a static `index.html` and does not require a build step.
