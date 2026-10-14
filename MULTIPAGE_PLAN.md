# Multi-Page Site Plan

**Goal:** Turn the current single-page directory into a multi-page Jekyll site where each top-level category is its own page. Single README stays for backwards compatibility + GitHub rendering, but is augmented with deep links into per-category pages.

**Status:** Phase 1 (sitemap + robots) shipped. Phase 2 (per-page split) described below — needs operator sign-off before execution since it changes the URL structure.

---

## Why multi-page

- SEO: each category becomes its own indexable URL → long-tail traffic (currently the single page gets a fraction of the keywords it should).
- Plausible: per-page analytics (instead of a single bucket).
- Maintainability: the operator and the curator can scope diffs to a single category.
- Linking: external sites can deep-link to a specific category.

## Jekyll scaffold

```
_config.yml
CNAME
robots.txt
sitemap.xml
index.md               # landing page with intro + cards linking to each category
pages/                # one file per category
    essential-reading.md
    node-installation.md
    backups-and-recovery.md
    self-hosting-solutions.md
    managed-cloud-hosting.md
    lightning-network-implementations.md
    node-management-web-interfaces.md
    security-tools.md
    node-management-tools.md
    node-services.md
    channel-management.md
    tutorials-and-guides.md
    liquidity-management.md
    network-explorers.md
    communities.md
    watchtowers.md
    mempool-resources.md
    educational-resources.md
    network-statistics.md
    further-reading.md
```

Each `pages/*.md` file uses Jekyll frontmatter:

```yaml
---
layout: default
title: Node Installation
permalink: /getting-started/node-installation/
---
```

`index.md` becomes the landing page; each `pages/*.md` is rendered as a static page with shared navigation (top-bar menu) and the category content pulled from the existing README section.

## URL strategy

Option 1 (recommended): **mirror current anchors as real paths** so existing deep links don't break.

- `/#node-installation` → `/getting-started/node-installation/`
- `/#self-hosting-solutions` → `/getting-started/self-hosting-solutions/`

Option 2: simpler top-level flat paths — `/node-installation/`, `/self-hosting-solutions/`.

**Pick option 2 if SEO testing shows existing anchors get no traffic.** Plausible data isn't set up yet — when the Plausible API token is available, use that to decide.

## Implementation phases

1. **Phase 1 — Shipped** (this PR): `sitemap.xml` + `robots.txt` + this plan doc + intro + `last verified` markers per section.
2. **Phase 2 — Pending operator sign-off**: scaffold `_layouts/category.html`, create the `pages/` folder with stub files (each linking to its section anchor for now).
3. **Phase 3 — Pending operator sign-off**: split README content into per-page files; remove duplicates from README (or keep README as the canonical "everything in one place" view + per-page as the categorized view).
4. **Phase 4 — Pending Plausible token**: add per-page analytics, validate URL strategy with real traffic.

## Risk

- README is also rendered by GitHub on the repo page; if we delete sections from it, GitHub view breaks. Keep README as the canonical source and have the per-page files `include` the README section via a Jekyll generator. Decide during Phase 2.

## Decision needed

- **Option 1 (preserve anchors)** vs **Option 2 (flat paths)** for per-page URLs.
- Whether to split README content or keep README canonical + per-page mirrors.

See also: `STAG.md` in the repo for snapshot/sweep/digest status.