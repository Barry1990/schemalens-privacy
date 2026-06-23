# SchemaLens Privacy Policy Site

This folder contains the public privacy policy page for Microsoft Store submission.

Recommended GitHub Pages URL:

```text
https://<github-username>.github.io/schemalens-privacy/
```

## Publish

Create a new public GitHub repository named `schemalens-privacy`, then run:

```powershell
cd store-pages\schemalens-privacy
git init
git branch -M main
git add .
git commit -m "Publish SchemaLens privacy policy"
git remote add origin https://github.com/<github-username>/schemalens-privacy.git
git push -u origin main
```

Then open the repository on GitHub:

```text
Settings -> Pages -> Build and deployment -> Source: Deploy from a branch -> Branch: main / root
```

Use the resulting GitHub Pages URL as the Microsoft Partner Center privacy policy URL.
