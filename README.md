# SHMB Digital Marketing — Website

Static site for [shmbmarketing.ca](https://shmbmarketing.ca), deployed on Vercel.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `audit.html` | The Content Clarity Audit (offer page) |
| `about.html` | About / Sonya Berns |
| `404.html` | Not-found page |

No build step — plain HTML/CSS/JS, deployed as static files. `vercel.json` enables clean URLs (e.g. `/audit` instead of `/audit.html`).

## Local preview

Any static file server works, e.g.:

```
npx serve .
```

## Deployment

Hosted on Vercel, connected to this repository. Pushes to the production branch deploy automatically; other branches get a preview deployment.

Custom domain `shmbmarketing.ca` (registered at GoDaddy) is pointed at Vercel via DNS — see Vercel project → Settings → Domains for the current record configuration.

## Adding a case study

See [`CASE_STUDY_TEMPLATE.md`](./CASE_STUDY_TEMPLATE.md) for what's needed to add a new case study to the "The Work" section of `about.html`.
