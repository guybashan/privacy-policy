# Privacy Policy – Stack Tracker

This repository hosts the **privacy policy** for the app **Stack Tracker**.

- **Live policy:** [https://guybashan.github.io/privacy-policy/](https://guybashan.github.io/privacy-policy/)
- Use that URL in the app (Settings → Privacy policy), and in Google Play / App Store listing.

## Repo contents

- `index.html` – the privacy policy (HTML)
- `README.md` – this file

## Enabling the live URL (GitHub Pages)

1. In this repo on GitHub, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two, the policy is available at:

   **https://guybashan.github.io/privacy-policy/**

No build step required; GitHub Pages serves the static files as-is.

---

## First-time setup (create repo and push)

Run from the `privacy-policy` folder:

```bash
cd /Users/columbo/dev/privacy-policy

git init
git add .
git commit -m "Initial commit: Stack Tracker privacy policy"

# Create the repo on GitHub (e.g. github.com/guybashan/privacy-policy), then:
git remote add origin https://github.com/guybashan/privacy-policy.git
git branch -M main
git push -u origin main
```

Then enable **GitHub Pages**: repo **Settings → Pages** → Source: **Deploy from a branch** → branch **main**, folder **/ (root)** → Save.
