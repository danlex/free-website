# Codex Free Website

Build and publish a personal website for free with:

- Codex for editing
- GitHub for version control
- GitHub Pages for hosting
- Your own domain for the final URL

Live site: [danlex.github.io/codex-free-website](https://danlex.github.io/codex-free-website/)

Repo: [github.com/danlex/codex-free-website](https://github.com/danlex/codex-free-website)

## What This Repo Is

This repo has two jobs:

- The repo root publishes a polished explainer site on GitHub Pages.
- The actual no-framework website starter lives in `templates/no-framework`.

That split is intentional. The explainer helps people understand the flow. The starter folder is the part you copy into your own repo when you want to build your site.

## Start Here

1. Clone this repo or browse it on GitHub.
2. Open `templates/no-framework`.
3. Copy those starter files into your own repo or working folder.
4. Open that starter in Codex and customize it.
5. Push to GitHub and enable GitHub Pages.
6. Add your custom domain when you are ready.

If you only want the website template, start from:

- `templates/no-framework/index.html`
- `templates/no-framework/styles.css`
- `templates/no-framework/script.js`
- `templates/no-framework/CNAME.example`

## Repo Layout

- `index.html`
  Published homepage and explainer for the starter.
- `how-it-works.html`
  Secondary explainer page with the same flow and supporting guidance.
- `how-it-works.css`
  Shared layout and component system.
- `home-light.css`
  Light-theme overrides for the Apple-like white layout with TVL-style branding.
- `templates/no-framework/`
  The actual starter you should use for your own website.
- `QUICKSTART.md`
  The shortest path from starter files to GitHub Pages and a custom domain.
- `prompts/first-codex-prompt.md`
  A ready-to-use prompt for customizing the starter in Codex.
- `content/`
  LinkedIn post and slide assets for sharing the project.

## Why No Framework

- No install step
- No build step
- Works directly with GitHub Pages
- Easy to edit in Codex
- Easy to hand off or maintain later

If the site is mostly content, links, projects, and contact details, plain HTML, CSS, and JavaScript are usually enough.

## Recommended First Prompt

Use this after opening the starter files in Codex:

```text
Turn this starter into a personal website for [name], a [role].

Constraints:
- Keep it compatible with GitHub Pages
- Keep it as static HTML, CSS, and JavaScript
- No framework, no build step

Make these changes:
- Rewrite all placeholder copy
- Add a stronger hero section
- Add 3 projects with believable summaries
- Update the links and contact section
- Improve the palette and typography for [industry/style]
- Tighten mobile spacing
```

## Documentation

- Quickstart: [QUICKSTART.md](QUICKSTART.md)
- Explainer page: [how-it-works.html](how-it-works.html)
- Starter prompt: [prompts/first-codex-prompt.md](prompts/first-codex-prompt.md)
- GitHub Pages custom domain docs: [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)

## Publish Checklist

- Replace the placeholder content
- Add your real links and contact info
- Update the title, description, and social preview image
- Rename `CNAME.example` to `CNAME` when you need a custom domain
- Set the domain inside the `CNAME` file
- Enable GitHub Pages and HTTPS

## License

MIT
