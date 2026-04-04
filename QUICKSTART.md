# Quickstart

This is the easiest way to use this repo.

## The short version

1. Copy `templates/no-framework`
2. Edit the files in Codex
3. Push to GitHub Pages

## 1. Copy the starter

Use these files:

- `templates/no-framework/index.html`
- `templates/no-framework/styles.css`
- `templates/no-framework/script.js`
- `templates/no-framework/CNAME.example`

If you are on macOS or Linux:

```bash
git clone https://github.com/danlex/codex-free-website.git
cd codex-free-website
mkdir ../your-site
cp -R templates/no-framework/. ../your-site/
cd ../your-site
```

## 2. Edit the starter in Codex

Open these files:

- `index.html`
- `styles.css`
- `script.js`

Then start with [prompts/first-codex-prompt.md](prompts/first-codex-prompt.md).

## 3. Push to GitHub

From your new website folder:

```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```

## 4. Enable GitHub Pages

In GitHub:

1. Open `Settings`
2. Open `Pages`
3. Choose `Deploy from a branch`
4. Select `main` and `/ (root)`
5. Save

## 5. Add your custom domain

When you are ready:

1. Rename `CNAME.example` to `CNAME`
2. Put your domain in the file
3. Commit and push
4. Add the domain in GitHub Pages settings
5. Enable HTTPS once it is available

Official docs:

- [Configuring a custom domain for your GitHub Pages site](https://docs.github.com/articles/setting-up-a-custom-domain-with-github-pages)
- [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)

## Common mistakes

- Editing the explainer in the repo root instead of the starter in `templates/no-framework`
- Forgetting to rename `CNAME.example`
- Publishing before replacing the placeholder copy
