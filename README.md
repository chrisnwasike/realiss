# Realiss Language School

Marketing website for Realiss Language School in Awka. It is a single static page that presents the four languages taught, the course options, what students get on enrolment, and how to find the school.

## Project structure

```
realiss/
├── index.html     # The whole site (HTML + inline CSS/JS)
├── .gitignore     # Ignores every folder whose name starts with a period
├── .docs/         # Internal reference docs (git-ignored)
└── .raw/          # Proposals and working prompts (git-ignored)
```

## Running locally

The site is plain HTML with no build step.

1. Place the project in `C:\xampp\htdocs\realiss`.
2. Start Apache from the XAMPP control panel.
3. Open <http://localhost/realiss/>.

You can also open `index.html` directly in a browser.

## Notes

- Fonts (Bricolage Grotesque and Source Sans 3) load from Google Fonts, so an internet connection is needed to see them as designed.
- `.docs/` and `.raw/` are intentionally excluded from version control.

## Deployment

Upload `index.html` to any static host or to the web root of a cPanel account.
