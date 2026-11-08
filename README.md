# Habbo Tools

Fan tools powered by the **official Habbo Web API**.

## Features

| Tool | What it does |
|------|----------------|
| **Profile** | Lookup any public Habbo — avatar, level, badges, friends, groups, rooms |
| **Marketplace** | Average sold price & volume via the batch marketplace endpoint |
| **Badge owners** | Owner count for any badge code (staff/VIP excluded) |
| **Hot looks** | Current popular avatar looks on the selected hotel |

Supports all main hotels: `.com`, `.es`, `.com.br`, `.de`, `.fi`, `.fr`, `.it`, `.nl`, `.com.tr`.

## Live site

After enabling **GitHub Pages** (Settings → Pages → Deploy from branch `main` / root):

**https://sleekset.github.io/habbo-tools/**

Or open `index.html` locally in any browser — no build step.

## API endpoints used

- `GET /api/public/users?name=`
- `GET /api/public/users/{id}/profile` (+ badges, friends, groups, rooms)
- `POST /api/public/marketplace/stats/batch`
- `GET /api/public/badge/owners/{code}`
- `GET /api/public/lists/hotlooks`
- Avatar imaging + badge images from Habbo CDN

## Not affiliated

This is an unofficial fan project. Habbo is a trademark of Sulake Corporation Oy.
