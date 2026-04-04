# Quickstart

This is the shortest path from this repo to your own live website.

## 1. Understand the repo split

This repo has two parts:

- The repo root publishes the explainer site on GitHub Pages.
- The website starter you should customize lives in `templates/no-framework`.

If you want your own site, start from `templates/no-framework`.

## 2. Copy the starter into your own project

Create a new folder or repo for your site, then copy these files from `templates/no-framework` into its root:

- `index.html`
- `styles.css`
- `script.js`
- `CNAME.example`

If you are on macOS or Linux, one option is:

```bash
git clone https://github.com/danlex/codex-free-website.git
cd codex-free-website
mkdir ../your-site
cp -R templates/no-framework/. ../your-site/
cd ../your-site
```

## 3. Open the starter in Codex

Start with:

- `index.html` for content and sections
- `styles.css` for layout, spacing, colors, and type
- `script.js` for small interactions only

Then use the starter prompt in [prompts/first-codex-prompt.md](prompts/first-codex-prompt.md).

## 4. Initialize your own GitHub repo

From your new website folder:

```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```

## 5. Enable GitHub Pages

In GitHub:

1. Open `Settings`
2. Open `Pages`
3. Under `Build and deployment`, choose `Deploy from a branch`
4. Select `main` and `/ (root)`
5. Save

Your site will publish to:

- `https://your-username.github.io/your-repo-name/`

If the repo name is `your-username.github.io`, it becomes a user site and publishes at the root domain instead.

## 6. Add your custom domain

1. Rename `CNAME.example` to `CNAME`
2. Put your domain in the file, for example:

```text
www.yourdomain.com
```

3. Commit and push
4. Set the custom domain in GitHub Pages settings
5. Enable HTTPS once GitHub offers it

For current DNS guidance, use GitHub’s official docs:

- [Configuring a custom domain for your GitHub Pages site](https://docs.github.com/articles/setting-up-a-custom-domain-with-github-pages)
- [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)

## 7. Iterate in Codex

Examples:

- `Turn this into a portfolio site for a product designer.`
- `Rewrite the copy so it sounds more direct and less generic.`
- `Add a projects section and improve mobile spacing.`
- `Make it feel more editorial and less like a generic landing page.`

## 8. Share it

Use:

- [content/linkedin-post.md](content/linkedin-post.md)
- [content/linkedin-slides.md](content/linkedin-slides.md)

## Common mistakes

- Editing the explainer in the repo root instead of the starter in `templates/no-framework`
- Forgetting to rename `CNAME.example`
- Expecting DNS changes to propagate instantly
- Publishing before replacing placeholder copy and links
