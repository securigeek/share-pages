# share-pages

Public-safe throwaway pages for SecuriGeek.

**Rule:** only content that can live on the open internet. No client names, no commercial briefs, no internal playbooks.

## URLs (after Pages is turned on)

- Landing: https://securigeek.github.io/share-pages/
- One share: https://securigeek.github.io/share-pages/`<slug>`/

## Turn Pages on (once)

1. Open https://github.com/securigeek/share-pages/settings/pages
2. Source: **Deploy from a branch**
3. Branch: `main` · folder: `/docs`
4. Save. Wait ~1–2 minutes.

Also add a `.nojekyll` file (already in this repo) so GitHub serves raw HTML.

## Add a page

```
docs/<slug>/index.html
```

Commit to `main`. The page appears at `/<slug>/`.

## Tear a page down

Delete `docs/<slug>/` and push. The URL dies with the next Pages build.

To take the whole site down: Settings → Pages → unpublish, or delete this repo.

## Do not put here

Internal Jules briefings, account lists, talk tracks, meeting transcripts.
Those stay on Drive / Notion / a protected Vercel preview.
