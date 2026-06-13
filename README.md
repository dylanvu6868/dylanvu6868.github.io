# dylanvu6868.github.io

Personal portfolio of **Vu Hai Duong (Vũ Hải Dương)** — AI / ML Engineer.

Single-file site (`index.html`): no build step, no dependencies. Bilingual EN/VI,
light/dark themes, restrained motion (reduced-motion safe), SEO + Open Graph, and a
live "Open source" section pulled from the GitHub API.

## Run locally
Just open `index.html` in a browser. (For the GitHub API section to fetch, any normal
`http(s)`/`file://` load works.)

## Edit
`index.html` is the source of truth. Text is bilingual via `data-vi` attributes; the
English copy lives in the HTML and the Vietnamese in `data-vi`.

## Deploy (GitHub Pages)
This repo is named `dylanvu6868.github.io`, so GitHub serves `index.html` at
`https://dylanvu6868.github.io/` automatically once pushed to the default branch.
Add your `assets/` files (see `assets/README.md`).
