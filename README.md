# echoNad3 portfolio

Static portfolio for [echonad3.github.io](https://echonad3.github.io/).

The site presents shipped work across web, browser extensions, PWAs, Cloudflare Workers, and Android while remaining fast, accessible, and free of analytics or client-side JavaScript.

## Featured work

- [Fitness Hub](https://echonad3.github.io/fitness_hub/) — offline-first workout tracker for web, PWA, and Android
- [No BS Summary](https://no-bs-summary.echonad3.workers.dev/) — YouTube summarizer for web, Chrome, PWA, and Android
- [echoTheme](https://marketplace.visualstudio.com/items?itemName=echoNad3.echonade3theme) — Visual Studio Code theme

## Local preview

Serve the repository root with any static file server, for example:

```sh
python -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Structure

- `index.html` — portfolio homepage
- `work/` — detailed project case studies
- `assets/styles.css` — shared responsive design system
- `assets/projects/` — project-owned brand assets

The site deploys directly from the `main` branch through GitHub Pages.
