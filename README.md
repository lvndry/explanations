# explanations

Published explanations, served as static pages at https://lvndry.github.io/explanations/.

Each explanation is a folder at the repo root with an `index.html` plus its supporting files (sections, styles, scripts). Its URL is `https://lvndry.github.io/explanations/<name>/`.

## How pages get here

Pages are published from a [Jazz](https://jazz-cli.vercel.app/) agent skill. Publishing copies the explanation's folder into this repo and commits it as `publish <name>`.

## Hosting

GitHub Pages serves `main` from `/`. The `.nojekyll` file turns off Jekyll, so files are served exactly as committed.

Everything in this repo is public.
