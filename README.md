# nuke-alert.com

Public marketing site and legal pages (Terms of Service, Privacy Policy) for the
[NukeAlert](https://nuke-alert.com) app.

## Structure

- `index.html` — landing page
- `terms/index.html` — Terms of Service (→ `nuke-alert.com/terms`)
- `privacy/index.html` — Privacy Policy (→ `nuke-alert.com/privacy`)
- `404.html` — fallback page
- `styles.css` — shared styles (dark theme + orange accent, matches the app)
- `assets/` — static assets (logo, etc.)
- `CNAME` — custom domain (`nuke-alert.com`)
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing

## Deployment

Served via GitHub Pages from the `master` branch root. Pushes to `master`
automatically publish to [nuke-alert.com](https://nuke-alert.com).

## Updating legal content

The source of truth for legal text is the [NukeAlert app repo](https://github.com/marpavlov2/NukeAlert)
at `legal/terms.md` and `legal/privacy.md`. When those are updated, mirror the
changes into `terms/index.html` and `privacy/index.html` here (and bump the
version / date in the `.doc-meta` block).

## Contact

- Support: help@nuke-alert.com
