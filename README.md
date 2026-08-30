# about-runtian-uk

Static About Me page for `about.runtian.uk`, hand-authored (not generated —
unlike `software-mirror`). Migrated off WordPress.com's block editor so the
page can be fully custom-styled and version-controlled.

- `index.html` / `styles.css` — the page. Edit directly; no build step.
- `CNAME` — GitHub Pages custom domain file. **Never delete** (see
  `docs/runtian-uk-website.md` gotcha #1 in the parent WebDevelop repo for why).
- LinkedIn section uses LinkedIn's official embeddable profile badge
  (`platform.linkedin.com/badges/js/profile.js`, `data-vanity="rwwu"`) —
  photo/name/headline + Follow button. LinkedIn does not offer a public API
  or RSS for a personal profile's post feed, so there is no live feed here.

This folder itself is the git working copy pushed to
`Micropeptide/about-runtian-uk` (same pattern as `demo-hello-page`).
