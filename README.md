# Community website

Source of the [Nuclear Science & Engineering Community](https://github.com/nuclear-community) website, served at **[nuclear-community.github.io](https://nuclear-community.github.io/)** via GitHub Pages.

## Stack

Deliberately boring and dependency-free:

- Plain HTML (`index.html`)
- One stylesheet (`styles.css`) — clean, Apple-inspired light design: white canvas, single blue accent, large type, hairline dividers
- No build step, no JavaScript, no external fonts or frameworks

This keeps the site fast, trivial to host, and editable by anyone who knows basic HTML/CSS — which is exactly the point for a community site.

## Run it locally

Just open `index.html` in a browser, or serve the directory:

```bash
# any static file server works, e.g.:
python -m http.server 8000
```

## Edit it

- Content lives in `index.html` (sections are commented).
- Colors, spacing, and the CSS atom logo live in `styles.css` (CSS custom properties at the top).
- Fixes and improvements go through pull requests — see our [contributing guide](https://github.com/nuclear-community/.github/blob/main/CONTRIBUTING.md).

## License

- Code: [MIT](LICENSE)
- Written content: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
