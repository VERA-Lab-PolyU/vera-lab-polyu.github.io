# VERA Lab Homepage

A custom Hugo website for VERA Lab — Trustworthy & Collaborative Intelligence — led by Prof. Yang (Veronica) Liu at The Hong Kong Polytechnic University.

## Preview locally

```bash
hugo server -D
```

Then open <http://localhost:1313/>.

## Production build

```bash
hugo --gc --minify
```

The generated site is written to `public/`.

## Deployment

The production site is published at <https://vera-lab-polyu.github.io/>.
Pushes to `main` trigger `.github/workflows/deploy-pages.yml`, which builds the
Hugo source and deploys the generated `public/` directory with GitHub Pages.

Before the first deployment, set the repository's Pages source to **GitHub
Actions** under **Settings → Pages**.

## Common updates

- Lab name and contact details: `hugo.yaml`
- Research directions: `data/research.yaml`
- Members, roles, links, and photos: `data/members.yaml`
- News: `data/news.yaml`
- Selected publications: `data/publications.yaml`
- Featured work: `data/featured.yaml`
- Homepage structure: `layouts/index.html`
- Visual system: `assets/css/main.css`

## Site structure

The homepage is intentionally selective: it introduces the lab, highlights three current projects, and routes visitors into focused sections.

- `/research/` — research agenda and directions
- `/people/` — principal investigator, academic advisor, and researchers
- `/publications/` — selected papers with paper/code links
- `/news/` — awards, publications, and lab updates
- `/join/` — roles, application guidance, and contact

The section front matter lives in `content/<section>/_index.md`; the corresponding page layouts live in `layouts/<section>/list.html`.

## Design research

The homepage structure was informed by a review of 11 official AI and research-lab websites. The evidence and implementation recommendations are recorded in `docs/lab-homepage-design-benchmarks.md`.

For member photos, add a web-accessible image URL to the member's `photo` field. If `photo` is omitted, the site displays the member's initials so the layout remains complete.
