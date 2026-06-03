# cfo-centre-reports

Public host for CFO Centre **AI Profit Leak Scan** reports sent to prospects before a call.

- One folder per prospect: `/<company-slug>/index.html`
- Shared brand assets at `/assets/` (referenced as `../assets/...` from each report)
- Served via GitHub Pages: `https://dopamine-digital.github.io/cfo-centre-reports/<company-slug>/`
- Every report is `noindex` + repo-wide `robots.txt` Disallow, so reports never get indexed; the slug is the only gate (unguessable per prospect).
- Tracking: each report beacons `opened` to `docs.dopaminedigital.io/track` (Telegram + Slack #audit-logs). Works cross-origin.

## Publish a report
Built by the `profit-leak-scan` skill (ops-playbook). To publish a rendered report:

```
ops-playbook/skills/profit-leak-scan/publish_report.sh <company-slug> /path/to/report.html
```

Optional white-label domain later: point a bought domain (e.g. cfoassets.com) at this repo via CNAME; relative asset paths and the cross-origin beacon keep working unchanged. Not required.
