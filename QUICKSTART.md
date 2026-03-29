# Quick Starter

This is the shortest path from clone to live site.

## 1. Clone and open in Codex

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Open the folder in Codex.

## 2. Start with the default no-framework site

Edit these files:

- `index.html` for content and sections
- `styles.css` for colors, spacing, and layout
- `script.js` for small interactions

This is the recommended path for most users because it works with GitHub Pages directly and keeps setup minimal.

## 3. Customize the site

Open the repo root and start with [prompts/first-codex-prompt.md](/Users/adan/work/claude/code/codex-free-website/prompts/first-codex-prompt.md).

Keep it as plain HTML, CSS, and JavaScript so it stays easy to publish on GitHub Pages.

## 4. Create the GitHub repo

From the project root:

```bash
git init
git add .
git commit -m "Initial website starter"
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

Your site will be published on `https://your-username.github.io/your-repo-name/` unless this is a user site repo named `your-username.github.io`.

## 6. Add your domain

1. Rename `CNAME.example` to `CNAME`
2. Replace the placeholder value with your domain, for example:

```text
www.yourdomain.com
```

3. Commit and push the change
4. Verify the domain in GitHub if you want the safer setup GitHub recommends
5. In your domain provider DNS settings:

For a subdomain such as `www`:

- Add a `CNAME` record pointing `www` to `your-username.github.io`

For an apex domain such as `yourdomain.com`:

- Add `A` records pointing to GitHub Pages IPs
- Optionally add `AAAA` records for IPv6 support
- Optionally redirect apex to `www` at your registrar

GitHub Pages apex IPs:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

GitHub Pages apex IPv6 addresses:

- `2606:50c0:8000::153`
- `2606:50c0:8001::153`
- `2606:50c0:8002::153`
- `2606:50c0:8003::153`

Then set the custom domain in GitHub Pages settings and enable HTTPS once available.

## 7. Use Codex to iterate

Examples:

- "Turn this into a portfolio site for a product designer."
- "Rewrite the copy so it sounds more direct and less generic."
- "Add a testimonials section and improve mobile spacing."
- "Make this look more editorial and less startup landing page."

## 8. Share it

Use:

- [content/linkedin-post.md](/Users/adan/work/claude/code/codex-free-website/content/linkedin-post.md)
- [content/linkedin-slides.md](/Users/adan/work/claude/code/codex-free-website/content/linkedin-slides.md)

## Common mistakes

- Forgetting to rename `CNAME.example`
- Using a wrong DNS target
- Expecting domain changes to propagate instantly
