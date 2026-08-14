# AIM (AI Monitoring)

Public marketing site for [getaimonitoring.com](https://getaimonitoring.com).

Privacy-first developer AI governance. Community is free for personal projects
and public open source. Team and Enterprise are licensed fleets.

| Tier | Public price | Start |
|---|---|---|
| Community | Free (soft cap: 3 seats) | [Clone hawikk/aim](https://github.com/hawikk/aim) |
| Team | $12 / seat / month annual ($15 monthly, min 5) | `sales@getaimonitoring.com` |
| Enterprise | From $28 / seat / month | `sales@getaimonitoring.com` |

Community is a GitHub clone, not an access request.

```bash
git clone https://github.com/hawikk/aim.git
cd aim
./scripts/demo-stack-up.sh
```

This repo is the GitHub Pages tree for the landing page. Product source lives
in [hawikk/aim](https://github.com/hawikk/aim) (Apache-2.0 Community).

## Custom domain

- Apex + www: `getaimonitoring.com` (GitHub Pages, HTTPS enforced)
- `CNAME` file: `getaimonitoring.com`
- `www` 301s to apex; HTTP 301s to HTTPS
