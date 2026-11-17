# Lumamark · 光影標記 — public pages

Public, script-free pages for Lumamark (光影標記), used as the store listing's privacy policy link.

## Contents

| Path | Purpose |
| --- | --- |
| `index.html` | Landing page, links to the privacy policy |
| `privacy/index.html` | Privacy policy in English, Simplified Chinese (zh-Hans) and Hong Kong Traditional Chinese (zh-HK), including free and Pro/IAP disclosures |

## Rules

1. The policy text is **not** authored here. The free section is copied verbatim from the product repository's `docs/store/隐私摘要-三语.md` (three keys: offline, noCollection, noServer). The Pro/IAP section is copied verbatim from `docs/store/Pro隐私披露-三语.md`. Any wording change is made in the product repository first, then republished here.
2. The page combines the free privacy summary and the P8-06 Pro/IAP addendum on the same URL. The decision is recorded in the product repository's `docs/adr/0048-store-privacy-hosting.md`.
3. No scripts, no analytics, no external assets, no third-party requests. Plain HTML and CSS only.
4. Published via GitHub Pages from the `main` branch (root). `.nojekyll` keeps the files served as-is.

## Updating

Regenerate `privacy/index.html` from both product-repository sources, review the three languages sentence by sentence, then commit and let Pages redeploy.
