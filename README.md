# aronsonben.github.io

Minimal, earth-tone personal portfolio for Benito Aronson. This refresh archives the original HTML5 UP template inside `legacy/` and rebuilds the site with plain HTML + CSS.

## Stack
- Static `index.html`
- Custom stylesheet `styles.css` using the warm neutrals pulled from the archived `stylez.css`
- Local font `windowsregular` from `fonts_nu/` plus Ubuntu Mono via Google Fonts

## Structure
```
.
├── fonts_nu/          # self-hosted font files
├── legacy/            # previous site snapshot for reference
├── index.html         # new markup (bio, projects, contact)
├── styles.css         # earth-tone layout + responsive rules
└── README.md
```

## Local development
1. Serve the folder with any static server (`python -m http.server`, VS Code Live Server, etc.).
2. Edit `index.html` or `styles.css`; changes reload immediately.
3. Deploy by pushing to `master`, which GitHub Pages already hosts.

## Customization
- Update the hero copy, project list, and contact links directly in `index.html`.
- Palette + spacing tokens live at the top of `styles.css`.
- Replace the `.avatar` div with a headshot when you are ready (drop the asset anywhere sensible and update the markup).

## Legacy content
Everything from the previous build (HTML, assets, license, README, etc.) is preserved under `legacy/` if you ever need to reference or restore it.
