# Temple of Music and Silence (TOMAS)

Static site for MusicSilence.com — multi-use sanctuary for music, silence, yoga, art, and gathering.

## Deploy to Cloudflare Pages
1. Register musicsilence.com at [Cloudflare Registrar](https://dash.cloudflare.com/) (at-cost pricing).
2. In Cloudflare Dashboard → Workers & Pages → Create application → Pages → Connect to Git.
3. Select GitHub → vdmuresan/musicsilence.
4. Build settings: Framework preset = None, Build command = (empty), Output directory = /.
5. Deploy. Add custom domain once registered.

## Images
Concept renders live in `images/` as WebP and are referenced from `index.html`. The redesign brief is `docs/brief.md`.

## Donate
The donate band (`#donate`) and its navigation link stay in the page with the `hidden` attribute until a live payment link replaces the `DONATE_URL` comment. The button points at `#` until then.

Vision includes dome, cliffside complex with rotating restaurant and aquarium, gardens, meditation halls, nature paths, and multi-purpose performance spaces.
