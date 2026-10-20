# Chien-Sheng Chiang

Personal academic website, adapted from [Kuan-Hsun Tu's template](https://github.com/syun413/syun413.github.io) (layout inspired by [Seohong Park's website](https://seohong.me/)). Plain static HTML + CSS, no build step — open `index.html` directly or publish with GitHub Pages.

- `index.html`: biography, publications, experience, links.
- `assets/style.css`: layout and colors. Change `--link` / `--link-hover` for the accent color.
- `assets/images/profile.png`: profile photo.
- `assets/images/publications/`: publication teaser images.
- `assets/documents/CV.pdf`: CV.

## Deploy on GitHub Pages

1. Create a public repo named `<your-github-username>.github.io`.
2. `git remote add origin https://github.com/<user>/<user>.github.io.git && git push -u origin main`
3. Repo → Settings → Pages → Source: *Deploy from a branch*, `main` / root. The site appears at `https://<user>.github.io`.
