# RC Story Wiki

Source for **https://wiki.rcstoryshow.com** — the lore wiki of the RC Story Cinematic Universe (House Fluchel Studios).

Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/). Every push to `main` rebuilds and deploys the site through GitHub Actions (`.github/workflows/deploy.yml`).

## Editing
- Pages live in `docs/`. Edit any page on GitHub (pencil icon) and commit; the site updates in ~1 minute.
- New page: add the `.md` file in the right folder **and** add it to `nav:` in `mkdocs.yml`.
- Infobox: copy the `<div class="infobox" markdown>` block from any character page.
- Status badges: `<span class="status canon">Confirmed canon</span>` or `<span class="status wip">Dossier in progress</span>`.
- Amazon links: `https://www.amazon.com/dp/ASIN?tag=frederickgeor-20` in the page's "Get the rig" section.
- Only publish confirmed canon. Copilot/Cortana material stays out until Frederick confirms it.

See `EDITORS.md` for open review items (not published to the site).
