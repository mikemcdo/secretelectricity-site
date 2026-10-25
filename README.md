# secretelectricity.studio

The public site for Secret Electricity: app documentation, support information and
the privacy policy. Served by GitHub Pages at <https://secretelectricity.studio>.

Plain HTML and one stylesheet — no build step, no dependencies. Edit a file, push,
and the change is live within a minute.

| Path | Purpose |
|---|---|
| `index.html` | Landing page and app index |
| `typelock/` | TypeLock for Jira documentation |
| `support/` | Support contact and what to include in a report — the support URL required for a paid Marketplace listing |
| `privacy/` | Privacy policy — the privacy URL required for a Marketplace listing |
| `style.css` | Shared stylesheet, light and dark |
| `CNAME` | Custom domain for GitHub Pages |

To preview locally:

```bash
python3 -m http.server 8000
```
