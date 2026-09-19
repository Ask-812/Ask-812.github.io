# ask-812.github.io

Personal site for Arnav Kshirsagar — [ask-812.github.io](https://ask-812.github.io)

Three pages:

| Path | Purpose |
|---|---|
| `/` | Positioning, current role, selected work |
| `/projects` | Full project write-ups, caveats included |
| `/security` | Validated security research findings |

## Develop

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # static output to dist/
npm run preview
```

## Deploy

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds with Astro
and publishes `dist/` to GitHub Pages.

## Content rules

Every factual claim here traces back to `profile/MASTER_PROFILE.md` in the
`auto_application` repo. Before editing copy:

- Bounty figures are **awarded** amounts confirmed by the programme. Never round up.
- Never publish exploit code, affected code paths, or details of unresolved reports.
- Never state a submission count as a finding count.
- Caveats — team projects, take-home assignments, work that was never deployed —
  stay in the write-up rather than being dropped from it.
