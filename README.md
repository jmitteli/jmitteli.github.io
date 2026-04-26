# GitHub Pages Portfolio Site

Personal portfolio and learning diary for the Oamk Cloud Services course.

🌐 **Live site:** `https://jmitteli.github.io/` *(update this URL after enabling Pages)*

---

## File Structure

```
.
├── index.md                  # Homepage
├── _config.yml               # Jekyll/GitHub Pages config (theme, metadata)
├── .gitignore                # Keeps secrets and build files out of git
├── README.md                 # This file (not published to the site)
└── projects/
    ├── cloud.md              # Cloud services projects
    ├── web.md                # Web development projects
    └── homeserver.md         # Home server & automation projects
```

## How to Publish (GitHub Pages setup)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / `(root)`
5. Save — your site will be live in ~1 minute

## How to Add Content

- Add screenshots: drop `.png` files into a `/screenshots/` folder and link them in `.md` files
- Add new project pages: create a new `.md` file in `projects/`
- Update the learning diary table in `index.md`

## GitHub Flavored Markdown Features Used

- [x] Headings (`#`, `##`, `###`)
- [x] Tables (`| col | col |`)
- [x] Fenced code blocks (` ``` `)
- [x] Task lists (`- [x]`, `- [ ]`)
- [x] Blockquotes (`>`)
- [x] Links and images
- [x] Bold and italic (`**bold**`, `*italic*`)
- [x] Emoji (`:smile:`)

## ⚠️ Security Reminder

**Never commit secrets to this repo.** API keys, passwords, and tokens belong in `.env` files — which are listed in `.gitignore` and will not be pushed to GitHub.