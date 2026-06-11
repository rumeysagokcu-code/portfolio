# Rumeysa Gokcu — Portfolio

A single-page portfolio site (AI-native marketer & creator strategist). Built as plain HTML/CSS/JS — no build step, no dependencies.

## Contents

```
portfolio/
├── index.html              ← the whole site
├── .nojekyll               ← tells GitHub Pages to serve files as-is
├── assets/
│   ├── Rumeysa-Gokcu-CV.pdf
│   ├── img/                ← video poster frames
│   └── videos/             ← AI UGC clips (ugc-1/2/3.mp4)
└── README.md
```

## Publish it free on GitHub Pages

1. Go to https://github.com/new and create a repository.
   - To get the URL `https://<your-username>.github.io`, name the repo exactly `<your-username>.github.io`.
   - Otherwise any name works (e.g. `portfolio`) and the URL will be `https://<your-username>.github.io/portfolio/`.
   - Set it to **Public**.
2. On the new repo page click **uploading an existing file**, then drag in **everything inside this `portfolio` folder** (the `index.html`, `.nojekyll`, and the `assets` folder). Commit.
3. Open the repo's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**. Set branch to `main` and folder to `/ (root)`. Save.
5. Wait ~1 minute, then refresh — your live URL appears at the top of the Pages settings.

That's it. Any time you want to update content, edit `index.html` and re-upload.

## Editing the content

- **Social posts:** edit the `posts` array near the bottom of `index.html` (add/remove URLs, change platform/type labels).
- **AI UGC videos:** drop new `.mp4` files into `assets/videos/` and update the `<video>` tags in the AI UGC section.
- **Text/experience:** all in `index.html` — clearly labelled sections.

## Notes

- Social posts open the original Instagram/Facebook links in a new tab (live media can't be embedded reliably due to platform login walls, so clickable cards are used).
- All three AI UGC videos are self-hosted in the repo and play inline.
