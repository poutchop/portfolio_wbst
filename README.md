# Pout Chop Jal: portfolio

A hand-built single page. No build step and no libraries: `index.html` holds the markup, styles and scripts, and `img/` holds the photos.

## Deploy (replaces the old template)
1. In the GitHub repo `poutchop/portfolio_wbst`, delete the old files (or move them into an `old/` folder).
2. Upload `index.html`, the `img/` folder and this README to the repo root.
3. Vercel redeploys automatically from GitHub. Nothing to configure.

## Editing
- Text: search `index.html` for the sentence you want to change.
- Colors: the `:root` block at the top of the `<style>` tag. Each work area has its own color:
  green (`--canopy`) for climate and ventures, blue (`--nile`) for policy and research, ochre (`--ochre`) for product, design and honors.
- Project links: each project has one link to its document. Replace the shared Drive folder link with a link to the specific file.
- Contact form: it opens the visitor's email app with the message filled in. To receive messages without that step, create a free form at formspree.io and ask for the form to post there.

## Adding a paper to Research and writing
Open `index.html`, find the `<!-- Research & writing -->` section, copy one `<li class="pub">` block, paste it at the top of the list, and edit the year, title, authors, venue and link. Put the PDF in `docs/`. Set the label: `<span class="kind">Paper</span>`, `<span class="kind wip">Under review</span>` or `<span class="kind wip">In preparation</span>`. Commit to `main` and Vercel publishes it.
