# Contributing to Awesome Chrome Extensions

Thanks for contributing! This list stays useful because every entry is held to the same bar.

## What belongs here

- A browser extension for **Chrome / Chromium** that works under **Manifest V3** (still installable from the Chrome Web Store after the August 2026 MV2 purge is a good proxy).
- Live and maintained: a current Web Store listing, an official site, or an active public repo.
- Something a reasonable person would recommend to a friend — no knockoffs, no abandoned forks, no extensions whose business model is harvesting browsing data.

## What doesn't

- Dead or deprecated extensions (Pocket, HTTPS Everywhere, MV2-only builds) — these go in *Notable exclusions* at most.
- Extensions removed from the Web Store for policy/malware reasons.
- Duplicates of an existing entry — pick the better one and argue for a swap instead.

## How to propose an entry

1. Open an issue (or PR) with the extension's name, its Chrome Web Store URL, and one or two sentences on what it does.
2. Include the **license**: an SPDX identifier from the repo's LICENSE file (e.g. `MIT`, `GPL-3.0-only`), or `proprietary` for commercial/freemium products. If you can't verify the license, say so — don't guess.
3. Confirm it's verifiable: a live CWS listing, an official site, or a public repo as of your proposal date.

## Entry format

README bullets look like this:

```md
- [Name](https://chromewebstore.google.com/detail/slug/id) — One or two factual sentences. *(proprietary)*
```

- The `*(proprietary)*` marker is **required** for commercial/freemium/closed-source entries, and must not appear on open-source ones.
- Descriptions are factual, not marketing copy. Mention real limitations where they matter (e.g. MV3 capability reductions, premium-only features).
- Keep the JSON in sync: every README bullet must have a matching object in `data/chrome-extensions.json` and vice versa. CI checks this in both directions, plus section counts, TOC anchors, and the verified/unverified invariant.

## JSON schema

Each entry in `data/chrome-extensions.json` has exactly these keys:

| Key | Meaning |
| --- | --- |
| `name` | Official product name |
| `description` | 1–2 factual sentences |
| `license` | SPDX id, `proprietary`, or `null` (with the caveat in the description) |
| `category` | One of the README section slugs |
| `repo` | Public repo URL, or `null` |
| `homepage` | Primary link (prefer the CWS listing) |
| `official_site` | Vendor/project site, or `null` |
| `stars` | GitHub star count, or `null` when there is no public repo |
| `verified` | `true` when confirmed live via an official source |
| `unverified_reason` | Required when `verified` is `false`; must be absent/`null` when `true` |

## Code of conduct

Be kind, be honest, cite sources. Marketing spam and undisclosed affiliations will be removed.
