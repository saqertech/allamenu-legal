# AllaMenu — Legal Documents

Public, canonical source for the AllaMenu Privacy Policy and Terms of Service.

This repository is **public on purpose**: Apple and Google both require a publicly
reachable privacy policy URL on the store listing, and store reviewers must be able to
open these pages without signing in.

## Live URLs

| Document | English | العربية |
| --- | --- | --- |
| Privacy Policy | [`/privacy/`](https://saqertech.github.io/allamenu-legal/privacy/) | [`/privacy/ar/`](https://saqertech.github.io/allamenu-legal/privacy/ar/) |
| Terms of Service | [`/terms/`](https://saqertech.github.io/allamenu-legal/terms/) | [`/terms/ar/`](https://saqertech.github.io/allamenu-legal/terms/ar/) |

## Covered apps

- AllaMenu restaurant dashboard — `com.allamenu.app`
- Menu Points wallet — `com.allamenu.wallet`
- AllaMenu customer web menu — allamenu.com

## This is the canonical copy

`allamenu.com/privacy` and `allamenu.com/terms` **redirect here**. Edit the documents in
this repository only — never fork the text back into the Next.js app, or the two copies
will drift apart and the store listings will point at stale terms.

## No build step

Plain HTML and one stylesheet. No Jekyll, no npm, no CDN, no webfonts. Pushing to `main`
publishes via GitHub Pages.

These pages are load-bearing for app store compliance, so they are deliberately built to
render even if every external service is unreachable. Keep it that way — do not add a
dependency to this repo.

## Editing

1. Edit the English document.
2. Mirror the change into the Arabic document — the two must stay in sync.
3. Update the "Last updated" date at the top of **every** page you touched.
4. Commit and push to `main`. GitHub Pages redeploys automatically.

## Not legal advice

These documents were drafted for the AllaMenu product and have **not** been reviewed by a
lawyer. Before relying on them commercially, have counsel review at minimum the governing
law clause, the limitation of liability, and the loyalty points terms.
