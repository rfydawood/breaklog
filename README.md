# BreakLog website

The public website for **BreakLog** (formerly Hifz Class Tracker), a free class break and attendance tracker for hifz and madrasa teachers.

It will be served by GitHub Pages at **https://rfydawood.github.io/breaklog/**. The app itself stays at https://rfydawood.github.io/hifz-class-tracker/.

## Pages

| File | What it is |
| --- | --- |
| `index.html` | Landing page |
| `privacy.html` | Privacy policy (effective 27 October 2026) |
| `terms.html` | Terms of use (effective 27 October 2026) |
| `support.html` | Help and FAQ |
| `delete-account.html` | How account deletion works; links to the app's real deletion page |
| `404.html` | Shown by GitHub Pages for any missing page |
| `styles.css` | Shared colours, fonts and components for every page |
| `img/` | App screenshots (fictional example names only) |

Plain HTML and CSS: no build step and no scripts. Fonts come from Google Fonts. Links between pages are relative, so the site works under `/breaklog/` (only `404.html` uses `<base href="/breaklog/">`, because GitHub Pages serves it at any path).

## Rules for changes

- Never use real student, teacher, class or organization names, in text or in screenshots. Use clearly made-up examples like "Yusuf A." and "Morning Hifz Class".
- Only say what the live app does today. Anything not built yet is marked **Coming soon** (the organization section and the "Made to fit" templates).
- Check every page at phone width (390px) and desktop width, in light and dark mode.

## Publishing

Create a public GitHub repo named `breaklog`, push `main`, then turn on Pages (Settings → Pages → Deploy from a branch → `main`, `/ (root)`). `_mockup/` is git-ignored and is never published.
