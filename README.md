# Lumamark · 光影標記 — public pages

Public, script-free pages for Lumamark (光影標記), used as the store listing's privacy policy link.

## Contents

| Path | Purpose |
| --- | --- |
| `index.html` | Landing page, links to the privacy policy |
| `privacy/index.html` | Privacy policy in English, Simplified Chinese (zh-Hans) and Hong Kong Traditional Chinese (zh-HK) |

## Rules

1. The policy text is **not** authored here. It is copied verbatim from the product repository's `docs/store/隐私摘要-三语.md` (three keys: offline, noCollection, noServer). Any wording change is made there first, then republished here.
2. Free-version scope only. Purchase / restore / Microsoft Store communication wording belongs to the Pro track and must not be added here without a new decision in the product repository.
3. No scripts, no analytics, no external assets, no third-party requests. Plain HTML and CSS only.
4. Published via GitHub Pages from the `main` branch (root). `.nojekyll` keeps the files served as-is.

## Updating

Regenerate `privacy/index.html` from the product repository, review the three languages sentence by sentence, then commit and let Pages redeploy.
