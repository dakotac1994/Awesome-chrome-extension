# Choosing a Chrome Extension

A short guide to picking extensions you won't regret installing.

## 1. Check the manifest version

Chrome removed Manifest V2 extensions from the Chrome Web Store in **August 2026**. Any extension still installable from the Web Store today is on Manifest V3 (or was granted a narrow enterprise exception). If a blog post recommends an extension whose listing shows "last updated 2021", treat it as dead — this list only includes MV3-era extensions.

The practical consequence of MV3: content blockers now use `declarativeNetRequest` (fixed rule limits) instead of the old `webRequest` API. That's why the classic full-featured **uBlock Origin** is gone from the Chrome Web Store and only **uBlock Origin Lite** remains. If you need the full engine, that's a browser choice (Firefox still allows it), not an extension choice.

## 2. Read the permissions before you install

Chrome shows exactly what an extension can access at install time. Be skeptical of:

- **"Read and change all your data on all websites"** on extensions that don't obviously need it (a pomodoro timer has no business reading your banking page).
- Extensions from unknown publishers asking for broad host permissions *and* remote code execution patterns.

Prefer extensions whose permissions match their job: a JSON viewer needs access to the pages it formats; a password manager needs clipboard and autofill access; a new-tab page needs none of that.

## 3. Open source vs. proprietary

Open-source extensions (license shown in this list) let anyone audit what they do with your data — meaningful for privacy and security tools, where the whole point is trust. Proprietary extensions aren't automatically bad (1Password, Grammarly, and Loom are all serious products), but for a tracker blocker or a cookie manager, open source is a genuine feature. Entries labeled *(proprietary)* in the README are commercial or freemium products.

## 4. Check maintenance signals

On any Chrome Web Store listing, look at:

- **Updated date** — within the last year is healthy; 2022 or older is a red flag.
- **User count and rating** — popular doesn't mean safe, but abandoned usually means unpopular.
- **Developer responsiveness** — linked GitHub repo with recent commits beats a bare listing.

## 5. Fewer extensions is better

Every installed extension is code running in your browser with real privileges. Audit yours twice a year: `chrome://extensions` → remove anything you don't recognize or no longer use. Ten extensions you trust beat thirty you forgot about.

## Quick picks by need

| Need | Start with |
| --- | --- |
| Block ads/trackers | uBlock Origin Lite, Privacy Badger |
| Manage passwords | Bitwarden (open source), 1Password |
| Developer workflow | React/Vue/Redux DevTools, Wappalyzer |
| Tab overload | OneTab, Session Buddy, Tab Session Manager |
| Screenshots | GoFullPage, Awesome Screenshot |
| Readable web | Dark Reader, Just Read |
| Keyboard-driven browsing | Vimium |
