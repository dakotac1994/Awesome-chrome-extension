# Glossary

Terms you'll meet when reading about Chrome extensions.

- **Manifest V2 / V3** — The extension platform specification. Manifest V2 was the long-standing standard; **Manifest V3** (mandatory since 2024, with V2 purged from the Chrome Web Store in August 2026) changes background execution, network request handling, and remote code rules. Most user-visible breakage in 2024–2026 (ad blockers losing power, old extensions dying) traces back to this migration.
- **Content script** — JavaScript an extension injects into web pages to read or modify them. This is how ad blockers hide ads, how Dark Reader restyles pages, and how Vimium captures keystrokes.
- **Service worker** — In MV3, the replacement for persistent background pages. An event-driven script that wakes up when needed and is killed when idle. Extensions that need always-on state had to be re-architected for this.
- **Permissions** — Declared capabilities an extension requests at install time (`tabs`, `storage`, `cookies`, host access, …). Chrome shows these to the user; over-broad permissions are the #1 thing to check before installing.
- **Host permissions** — Permission to read/modify specific sites (`*://*.example.com/*`) or all sites (`<all_urls>`). The most sensitive permission class.
- **`declarativeNetRequest`** — The MV3 API for blocking/redirecting network requests via static rule lists (with strict rule-count limits). Replaces the blocking version of `webRequest` for ad and tracker blocking.
- **`webRequest`** — The MV2 API that let extensions observe *and modify* network traffic in real time. Still available in MV3 but only in observe-only mode for most extensions, which is why MV3 content blockers are less capable.
- **Side panel** — A persistent Chrome UI surface (opened via toolbar icon) where extensions can host full interfaces without a popup's lifetime limits. Used by note-taking and AI-assistant extensions.
- **Omnibox** — The address bar. Extensions can register keyword handlers (e.g. type a keyword + Tab) to search or trigger actions, as Sourcegraph does for code search.
- **Chrome Web Store (CWS)** — Google's official distribution channel and the primary install source referenced in this list.
- **Freemium** — Free core product with paid tiers. Labeled *(proprietary)* in this list, since the distributed extension is not open source.
- **Fingerprinting** — Identifying you by your browser's unique characteristics (canvas rendering, fonts, screen size) instead of cookies. Countered by extensions like JShelter and CanvasBlocker-style tools.
