# Privacy Policy Static Page

This repository contains a simple static privacy policy page for GitHub Pages.

## Files

- `index.html` - the privacy policy webpage served by GitHub Pages.

## Local Preview

Open `index.html` in a browser, or run a small local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Push to GitHub

Create a new empty repository on GitHub, for example `privacy-policy`, then run these commands from this folder:

```bash
git init
git branch -M main
git add index.html README.md
git commit -m "Add privacy policy page"
git remote add origin https://github.com/YOUR_USERNAME/privacy-policy.git
git push -u origin main
```

If you prefer SSH, use this remote instead:

```bash
git remote add origin git@github.com:YOUR_USERNAME/privacy-policy.git
```

## Deploy With GitHub Pages

After pushing:

1. Open the repository on GitHub.
2. Go to `Settings` > `Pages`.
3. Under `Build and deployment`, set `Source` to `Deploy from a branch`.
4. Set `Branch` to `main` and folder to `/ (root)`.
5. Click `Save`.

GitHub will publish the page at:

```text
https://YOUR_USERNAME.github.io/privacy-policy/
```

Use that URL anywhere a privacy policy URL is required.
