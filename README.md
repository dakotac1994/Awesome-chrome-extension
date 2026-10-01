# Awesome Chrome Extensions

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Entries](https://img.shields.io/badge/entries-80-blue)](data/chrome-extensions.json)
[![Verified](https://img.shields.io/badge/verified-80%2F80-brightgreen)](docs/status-changes.md)
[![CI](https://github.com/dakotac1994/Awesome-chrome-extension/actions/workflows/ci.yml/badge.svg)](https://github.com/dakotac1994/Awesome-chrome-extension/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A curated list of Chrome/Chromium browser extensions for the **Manifest V3 era** — developer tools, privacy guards, ad blockers, productivity boosters, tab managers, password managers, screenshot tools, design helpers, and everyday browsing upgrades.

> **Scope.** This list covers extensions for Chrome and Chromium-based browsers (Edge, Brave, Arc, Opera, etc.) that work under Manifest V3. Every entry was verified live on **2026-09-30** via its Chrome Web Store listing, official site, or public repo. Proprietary/freemium entries are explicitly labeled *(proprietary)*. Dead, deprecated, or removed extensions are documented under [Notable exclusions](#notable-exclusions), not listed as live.

## Contents

- [Developer Tools](#developer-tools)
- [Privacy & Security](#privacy--security)
- [Ad & Content Blocking](#ad--content-blocking)
- [Productivity](#productivity)
- [Tab Management & Sessions](#tab-management--sessions)
- [Password Managers](#password-managers)
- [Screenshots & Recording](#screenshots--recording)
- [Design & Color](#design--color)
- [New Tab, Reading & Misc](#new-tab-reading--misc)
- [Notable exclusions](#notable-exclusions)
- [Related](#related)
- [Contributing](#contributing)
- [License](#license)

## Developer Tools

*Extensions that make building and debugging the web easier: framework devtools, API tools, accessibility auditors, and page inspectors.*

(21 entries)

- [axe DevTools](https://chromewebstore.google.com/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd) — Web accessibility testing extension by Deque Systems. Freemium: core scanning free, advanced features paid. *(proprietary)*
- [BuiltWith Technology Profiler](https://chromewebstore.google.com/detail/builtwith-technology-prof/dapjbgnjinbpoindlpdmhochffioedbn) — Find out what the website you are visiting is built with, using the BuiltWith database (builtwith.com). *(proprietary)*
- [Cookie-Editor](https://chromewebstore.google.com/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm) — Efficient cookie manager with MV3 support (migration landed in v1.11.0; current v1.13.0).
- [CSS Peeper](https://chromewebstore.google.com/detail/css-peeper/mbnbehikldjhnfehhnaidhjhoofhpehk) — Inspect website styles in seconds: clean, focused CSS inspection for designers. By Sparkglare Sp. z o.o. (csspeeper.com). Freemium. *(proprietary)*
- [EditThisCookie (fork)](https://chromewebstore.google.com/detail/editthiscookie-fork/ihfmcbadakjehneaijebhpogkegajgnk) — MV3-native community fork of the classic EditThisCookie (original was MV2 and removed from CWS late 2024): view, edit and manage cookies. v1.7.11, updated Nov 16, 2025. The CWS listing describes itself as open source, but the linked repo has no license file, so no license is claimed here.
- [Enhanced GitHub](https://chromewebstore.google.com/detail/enhanced-github/anlikcnbgdeidpacdbdljnabclhahhmd) — Adds useful features on top of GitHub: repo size, per-file size, download links and copy-file-contents options.
- [JSONView](https://chromewebstore.google.com/detail/jsonview/gmegofmjomhknnokphhckolhcffdaihd) — Validates and formats JSON documents in the browser for readable inspection of API responses.
- [Library Detector](https://chromewebstore.google.com/detail/library-detector/cgaocdmhkmfnkdkbnckgmpopcbpaaejo) — Detects which JavaScript libraries are used on a page.
- [Lighthouse](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk) — Official Google Lighthouse extension: automated audits of performance, accessibility, best practices and SEO. Built into DevTools since 2019, still distributed as an extension and README-linked by GoogleChrome/lighthouse.
- [Octotree](https://chromewebstore.google.com/detail/octotree-github-code-tree/bkhaagjahfmjljalopjnoealnfndnagc) — GitHub code tree sidebar — 'GitHub on steroids'. v9.2.1, updated Sept 28, 2026. Freemium; official site octotree.io. *(proprietary)*
- [Postman Interceptor](https://chromewebstore.google.com/detail/postman-interceptor/aicmkgpgakddgnaphhhpliifpcfhicfo) — Capture requests from any website and send them to the Postman client; also forwards browser cookies and Chrome-restricted headers. v3.2.1, updated Aug 2025, by Postman Inc. *(proprietary)*
- [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) — React debugging tools that add React-specific panels to Chrome DevTools for inspecting component hierarchies, props and state. By Meta.
- [Redux DevTools](https://chromewebstore.google.com/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) — Redux DevTools provides power-ups for Redux development workflows; works with any architecture that handles state. Repo moved zalmoxisus/redux-devtools-extension -> reduxjs/redux-devtools.
- [Refined GitHub](https://chromewebstore.google.com/detail/refined-github/hlepfoohegkhhmjieoechaddaejaokhf) — Simplifies the GitHub interface and adds many useful features. v26.9.12 released ~Sept 12, 2026.
- [Responsive Viewer](https://chromewebstore.google.com/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb) — Show multiple screens at once for responsive design testing. v1.1.21 (Oct 2025); 'free forever, premium optional' (responsiveviewer.org). Source at skmail/responsive-viewer.
- [Sourcegraph](https://chromewebstore.google.com/detail/sourcegraph/dgjhfomjieaadpoljlnidmbgkdffpack) — Connect Sourcegraph to GitHub: open repos, compare revisions and search code from Chrome's omnibox. v24.3.8, updated Sept 11, 2026, by Sourcegraph. *(proprietary)*
- [User-Agent Switcher and Manager](https://chromewebstore.google.com/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) — Spoof browser user-agent strings per site or window, with randomization, Client Hints and navigator.userAgentData support. MV3, actively maintained (v0.7.1, Sept 2026; ~400k users).
- [VisBug](https://chromewebstore.google.com/detail/cdockenadnadldjbbgcallicgledbeoc) — Open-source web design debug tool by GoogleChromeLabs: point, click and edit any page visually. Official site visbug.web.app.
- [Vue.js devtools](https://chromewebstore.google.com/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd) — DevTools browser extension for Vue.js: inspect component tree, state and events. v7.x for Vue 3, v6 legacy for Vue 2.
- [Wappalyzer](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg) — Technology profiler that identifies the software stack behind any website (CMS, frameworks, analytics, etc.). v6.12.6, updated Aug 25, 2026, by Wappalyzer Pty Ltd. *(proprietary)*
- [Window Resizer](https://chromewebstore.google.com/detail/window-resizer/pplohohdkehokmecokhjlnbcjaclegok) — Resize the browser window to emulate various screen resolutions via preset and custom layouts. Listing text states 'Written on top of manifest version 3'. No license is stated by the publisher.

## Privacy & Security

*Take back control of your data: tracker blockers, cookie managers, fingerprinting defenses, and browser security guards.*

(9 entries)

- [Bitdefender Web Sage](https://chromewebstore.google.com/detail/bitdefender-web-sage/cfnpidifppmenkapgihekkeednfoenal) — Flags phishing and malware sites in search results and lists the trackers on each page. Formerly Bitdefender TrafficLight (renamed in 2026). Free and proprietary. *(proprietary)*
- [Consent-O-Matic](https://chromewebstore.google.com/detail/consent-o-matic/mdjildafknihdffpkfmmpnpoiajfjnjd) — Automatically answers GDPR cookie-consent pop-ups according to your saved preferences; built by privacy researchers at Aarhus University. Manifest V3.
- [Cookie AutoDelete V3](https://chromewebstore.google.com/detail/cookie-autodelete-v3/jofioghmpdcgiiobkhmdojhjbjiejfbd) — Automatically deletes cookies from closed tabs to limit cross-site tracking; the actively maintained Manifest V3 rewrite of the original Cookie AutoDelete.
- [DuckDuckGo Privacy Essentials](https://chromewebstore.google.com/detail/duckduckgo-search-tracker/bkdgflcldnnnapblkhphbgpggdiikppg) — Blocks third-party trackers and upgrades connections to HTTPS where possible; shows a privacy grade (A-F) for each site you visit.
- [Ghostery – Privacy Ad Blocker](https://chromewebstore.google.com/detail/ghostery-adblocker-for-pr/mlomiejdfkolichcflejclcbmpeaniij) — Blocks trackers and ads and shows exactly which trackers each page loads; open source and Manifest V3 compliant.
- [JShelter](https://chromewebstore.google.com/detail/jshelter/ammoloihpcbognfddfjcljgembpibcmb) — Restricts what browser JavaScript APIs reveal to websites to limit fingerprinting and tracking; an academic research project from Brno University of Technology.
- [Malwarebytes Browser Guard](https://chromewebstore.google.com/detail/malwarebytes-browser-guar/ihcjicgdanjaechkgeegckofjjedodee) — Blocks malware, scams, phishing pages, and trackers in real time. Free and proprietary. *(proprietary)*
- [Privacy Badger](https://chromewebstore.google.com/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp) — Tracker blocker from the EFF that learns to block invisible third-party trackers as you browse, stopping them from following you across sites.
- [SuperAgent - Automatic Cookie Consent](https://chromewebstore.google.com/detail/superagent-automatic-cook/neooppigbkahgfdhbpbhcccgpimeaafi) — Fills out cookie-consent forms automatically based on your preferences. Freemium: free for 40 pop-ups a week, paid plans for unlimited use. *(proprietary)*

## Ad & Content Blocking

*Clean up the web: ad blockers, sponsor skipping, and crowd-powered content fixes. Note: Chrome's Manifest V3 limits what blockers can do — uBlock Origin Lite is the MV3 build of the classic uBlock Origin.*

(7 entries)

- [Adblock Plus](https://chromewebstore.google.com/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb) — Long-running open-source ad blocker with filter-list subscriptions and an 'Acceptable Ads' allowlist. Manifest V3 compatible.
- [AdGuard AdBlocker](https://chromewebstore.google.com/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg) — Manifest V3 ad blocker with cosmetic filtering and tracker blocking backed by AdGuard filter lists.
- [Control Panel for Twitter](https://chromewebstore.google.com/detail/control-panel-for-twitter/kpmjjdhbcfebfjgdnpjagcndoelnidfj) — Reverts X/Twitter interface changes and strips algorithmic and promoted content from the timeline. Open source.
- [DeArrow](https://chromewebstore.google.com/detail/dearrow-better-titles-and/enamippconapkdmgfgjchkhakpfinmaj) — Replaces clickbait YouTube titles and thumbnails with crowdsourced descriptive alternatives; from the SponsorBlock developer.
- [Return YouTube Dislike](https://chromewebstore.google.com/detail/return-youtube-dislike/gebbhagfogifgggkldgodflihgfeippi) — Restores YouTube's hidden dislike counts via a crowdsourced API. Open source.
- [SponsorBlock](https://chromewebstore.google.com/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone) — Skips sponsored segments, intros, and other in-video annoyances on YouTube using crowdsourced timestamps.
- [uBlock Origin Lite](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh) — The Manifest V3 build of uBlock Origin for Chrome, using declarative rules with reduced filtering capability versus the full engine; the full MV2 build was removed from the Chrome Web Store.

## Productivity

*Get work done: web clippers, writing assistants, to-do lists, and time trackers.*

(9 entries)

- [Clockify Time Tracker](https://chromewebstore.google.com/detail/clockify-time-tracker/pmjeegjhjdlccodhacdgbgfagbpmccpe) — One-click time tracker with 50+ web-app integrations, idle detection, reminders, and a built-in Pomodoro timer.
- [Evernote Web Clipper](https://chromewebstore.google.com/detail/evernote-web-clipper/pioclpoplcdbaefihamjohnefbikjilc) — Clip articles, web pages, and screenshots into Evernote, with annotation tools and a distraction-free article view. *(proprietary)*
- [Grammarly: AI Writing Assistant and Grammar Checker](https://chromewebstore.google.com/detail/grammarly-ai-writing-assi/kbfnbcaeplbcioakkpcpgfkobkghlhen) — Checks grammar, spelling, and tone as you type across the web, with AI-powered rewriting suggestions. *(proprietary)*
- [LanguageTool](https://chromewebstore.google.com/detail/oldceeleldhonbafppcapldpdifcinji) — Multilingual grammar and style checker. In March 2026 the browser extension became premium-only; the web version stays free and the extension still works against a self-hosted server. *(proprietary)*
- [LeechBlock NG](https://chromewebstore.google.com/detail/leechblock-ng/blaaajhemilngeeffpbfkdjjoefldkok) — Free site blocker with up to 30 block sets on schedules or time limits, lockdown mode, delay pages, and password-protected options.
- [Notion Web Clipper](https://chromewebstore.google.com/detail/notion-web-clipper/knheggckgoiihginacbkhaalnibhilkk) — Save any web page, link, or image directly into your Notion workspace for later reference. *(proprietary)*
- [Pace](https://chromewebstore.google.com/detail/acgkenbhfmpcoelnfihoaicgnepneplj) — Minimalist MIT-licensed Pomodoro timer (MV3): plan work/break sessions and it shows the clock time you'll finish, with ambient sounds and a gentle full-screen break.
- [Todoist for Chrome](https://chromewebstore.google.com/detail/todoist-for-chrome-planne/jldhpllghnbhlbpcmnajkpdmadaolakh) — Save any page as a task and manage your Todoist to-do list, planner, and calendar without leaving the browser. *(proprietary)*
- [Toggl Track](https://chromewebstore.google.com/detail/toggl-track-productivity/oejgccbfbmkkpaidnkphaiaecficdnfn) — One-click timers embedded in 100+ web apps, with a built-in Pomodoro timer, idle detection, reminders, and detailed reports.

## Tab Management & Sessions

*Tame tab overload: session managers, tab organizers, and automatic tab discarders.*

(7 entries)

- [OneTab](https://chromewebstore.google.com/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall) — Converts all open tabs into a single list to cut clutter and memory use; restore tabs individually or all at once. (Listed only in this category per dedup rule.) *(proprietary)*
- [Session Buddy](https://chromewebstore.google.com/detail/session-buddy-tab-bookmar/edacconmaakjimmfgnblocblbcdcpbko) — Privacy-first session manager: save, organize, and restore sessions, tabs, and bookmarks. v4.0.0 is Manifest V3 compliant. *(proprietary)*
- [Tab Manager Plus for Chrome](https://chromewebstore.google.com/detail/tab-manager-plus-for-chro/cnkdjjdmfiffagllbiiilooaoofcoeff) — Finds open tabs across windows, spots duplicates, and caps tabs per window (rated 4.7 on the CWS). *(proprietary)*
- [Tab Session Manager](https://chromewebstore.google.com/detail/tab-session-manager/iaiomicjabeggjcfkbimgmglanimpnae) — Auto-saves browser sessions with tagging, import/export, and cloud sync; ships Chrome MV3 and Firefox builds.
- [Tab Wrangler](https://chromewebstore.google.com/detail/tab-wrangler/egnjhciaieeiiohknchakcodbpgjnchh) — Auto-closes tabs idle past a configurable timer into the Tab Corral for later restore; renders Chrome tab groups since v8.2.
- [Toby](http://chromewebstore.google.com/detail/toby-tab-management-tool/hddnkoipeenegfoeaoibdmnaalmgkpip) — Visual workspace that saves tab sessions into drag-and-drop collections on every new tab, with cloud sync; free tier holds 60 tabs. *(proprietary)*
- [Workona](https://www.workona.com) — Workspaces that persist tabs, docs, and tasks per project, with team sharing. Free tier reduced to 5 workspaces in 2026; Pro is $8/mo. *(proprietary)*

## Password Managers

*Log in securely: vault-backed password managers with autofill for Chrome.*

(5 entries)

- [1Password – Password Manager](https://chromewebstore.google.com/detail/1password-–-password-mana/aeblfdkhhhdcdjpifhhbdiojplfjncoa) — Commercial password manager with autofill, password generation, and passkey support. Requires a 1Password membership. *(proprietary)*
- [Bitwarden](https://chromewebstore.google.com/detail/bitwarden-password-manage/nngceckbapebfimnlniiiahkandclblb) — Open-source password manager with unlimited vault items and devices on the free tier, autofill, and cross-device sync.
- [Dashlane](https://chromewebstore.google.com/detail/dashlane-%E2%80%94-password-manag/fdjamakpfbbddfjaooikfcpapjohcfmg) — Commercial password manager with autofill, password generation, and dark-web monitoring. *(proprietary)*
- [KeePassXC-Browser](https://chromewebstore.google.com/detail/keepassxc-browser/oboonakemofpalcgghocfoadofidjkkk) — Official browser companion for the KeePassXC desktop password manager, pairing over native messaging so the vault stays local.
- [LastPass: Free Password Manager](https://chromewebstore.google.com/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd) — Commercial password manager with autofill, password generation, and cross-device sync. *(proprietary)*

## Screenshots & Recording

*Capture and share: full-page screenshots, annotated captures, and screen recording.*

(6 entries)

- [Awesome Screenshot](https://chromewebstore.google.com/detail/awesome-screen-recorder-s/nlipoenfbbikpbjkfpfillcgkoblgpmj) — Screenshot plus screen recorder with annotations; freemium. *(proprietary)*
- [FireShot](https://chromewebstore.google.com/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg) — Full-page webpage screenshots saved to PDF or image with an editor; free core plus a Pro edition. *(proprietary)*
- [GoFullPage](https://chromewebstore.google.com/detail/gofullpage-full-page-scre/fdpohaocaechififmbbbbbknoalclacl) — Captures full-page screenshots of any tab with one click; exports to PNG/PDF with a premium editor. *(proprietary)*
- [Loom](https://chromewebstore.google.com/detail/loom-%E2%80%93-screen-recorder-sc/liecbddmkiiihnedobmlmillhodjkdmb) — Screen, camera, and mic recorder with instant share links; free Starter tier (720p, 25 videos). Rated 4.6/5 on the CWS. *(proprietary)*
- [Nimbus Screenshot](https://chromewebstore.google.com/detail/nimbus-screenshot/bpconcjcammlapcogcnnelfmaeghhagj/) — Full-page and region screenshots with annotations and screen recording; blur tool requires Pro ($60/yr). The Nimbus brand rebranded to FuseBase in 2026. *(proprietary)*
- [Screencastify](https://chromewebstore.google.com/detail/screencastify-screen-vide/mmeijimgabbpbgpdklnllpncmdofkcpn) — Screen and webcam video recorder aimed at classrooms and async teams, with Google Drive export. *(proprietary)*

## Design & Color

*For designers and the design-curious: color pickers, font identifiers, rulers, and pixel-perfect overlays.*

(8 entries)

- [ColorPick Eyedropper](https://chromewebstore.google.com/detail/colorpick-eyedropper/ohcpnigalekghcmgcdcenkpelffpdolg) — Zoomed eyedropper & color chooser for selecting color values from webpages. Open-source project by qufighter; the repo has no license file, so no license is claimed here.
- [ColorZilla](https://chromewebstore.google.com/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp) — Advanced eyedropper, color picker, CSS gradient generator and page color analyzer; samples colors from anywhere on screen. *(proprietary)*
- [Dimensions](https://chromewebstore.google.com/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj) — Measure between images, inputs, text and other elements on any page in pixels. By Felix Niklas; open source at mrflix/dimensions. v3.0.1, updated Oct 7, 2025.
- [Fonts Ninja](https://chromewebstore.google.com/detail/fonts-ninja/eljapbgkmlngdpckoiiibecpemleclhh) — Identify fonts from any website, bookmark and organize them, see font details, foundry and similar fonts. v8.0.4, updated 2025-07-10; official site fonts.ninja. *(proprietary)*
- [Page Ruler Redux](https://chromewebstore.google.com/detail/page-ruler-redux/giejhjebcalaheckengmchjekofhhmal) — Draw a ruler to get pixel dimensions and positioning of elements on any web page. Community fork of the original Page Ruler with Mixpanel/ad-tracking removed.
- [PerfectPixel](https://chromewebstore.google.com/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi) — Overlay a semi-transparent design mockup on the live page for pixel-perfect comparison (opacity, blend modes, per-domain layers). By WellDoneCode; 350k+ users. Freemium: Pro adds unlimited layers, rotation, dark theme. *(proprietary)*
- [Site Palette](https://chromewebstore.google.com/detail/site-palette/pekhihjiehdafocefoimckjpbkegknoh) — Generates a color palette from any website for designers to use as reference; shareable palette links and downloadable previews. *(proprietary)*
- [WhatFont](https://chromewebstore.google.com/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm) — The easiest way to identify fonts on web pages: hover any text to see font family, size, weight and color. *(proprietary)*

## New Tab, Reading & Misc

*Upgrade everyday browsing: new-tab dashboards, reader modes, dark mode everywhere, keyboard navigation, and handy utilities.*

(8 entries)

- [Dark Reader](https://chromewebstore.google.com/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh) — Open-source extension that analyzes pages and generates a dark mode for every website to reduce eyestrain.
- [Honey: Automated Coupons & Rewards](https://chromewebstore.google.com/detail/honey-automated-coupons-r/bmnlcjabgnpnenekpadlanbbkooimhnj) — Auto-applies coupon codes at checkout across 30,000+ sites, with rewards and price-drop tracking (17M+ users). *(proprietary)*
- [Just Read](https://chromewebstore.google.com/detail/just-read/dgmanlpmmkibanfdgjocnabmcaclkmod) — Customizable reader view that strips ads, popups, and page styling from articles; optional AI summarization and a Premium tier for saving/sharing reader views.
- [Momentum](https://chromewebstore.google.com/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca) — Replaces the new tab with a calm dashboard: daily photo, focus prompt, to-do list, weather, and shortcuts; Plus tier adds task-manager integrations and AI features. *(proprietary)*
- [Rakuten: Get Cash Back For Shopping](https://chromewebstore.google.com/detail/rakuten-get-cash-back-for/chhjbpecpncaggjpdakmflnfcopglcmi) — Activates cash back at 3,500+ stores with one click, plus automatic coupon codes and price comparison. *(proprietary)*
- [Read Aloud: A Text to Speech Voice Reader](https://chromewebstore.google.com/detail/read-aloud-a-text-to-spee/hdhinadidafjejdhmfkjgnolgimiaplp) — One-click text-to-speech for web articles in 40+ languages, using browser voices or optional cloud AI voices; open source.
- [Surfingkeys](https://chromewebstore.google.com/detail/surfingkeys/gfbliohnnapiefjpjlpjnehglfpaknnc) — Vim-style keyboard control plus JavaScript-configurable custom keymaps, session management, and page capture (rated 4.7 on the CWS).
- [Vimium](https://chromewebstore.google.com/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb) — Keyboard-driven browsing in the spirit of Vim: scroll, open links, search tabs, and manage windows without the mouse.

## Notable exclusions

Extensions deliberately left out, with reasons. Being excluded here is not a judgment of quality — only of fit for a Manifest V3 Chrome list verified in September 2026.

| Extension | Why it's not listed |
| --- | --- |
| Pocket | Discontinued by Mozilla (~July 2025); the service shut down. |
| HTTPS Everywhere | Deprecated by the EFF; HTTPS is now the web default. |
| The Great Suspender | Removed from the Chrome Web Store in 2021 for malware after an ownership change. |
| uMatrix | Development ended in 2020; removed from the CWS in the August 2026 Manifest V2 purge. |
| NoScript | Manifest V2; removed from the CWS in the MV2 purge. |
| Decentraleyes | Manifest V2; non-functional on modern Chrome. |
| ClearURLs | Original MV2 build removed from the CWS; the MV3 migration is unfinished. |
| LocalCDN | Chrome build is Manifest V2 and the developer has no MV3 plans. |
| CanvasBlocker | The official build is Firefox-only; the Chrome lookalike was removed from the CWS. |
| Web Vitals | Retired by Google (Jan 2025); its features moved into the DevTools Performance panel. |
| Marinara (Pomodoro) | Abandoned (last updated 2021); gone in the MV2 purge. Pace is the listed MV3 alternative. |
| EditThisCookie (original) | Manifest V2; removed from the CWS in late 2024. The community fork is listed instead. |
| uBlock Origin (full) | MV2 build removed from the CWS (Aug 2026); only uBlock Origin Lite (MV3) remains for Chrome. |
| Privacy Possum | Discontinued EFF experiment. |
| Cookie AutoDelete (original) | Manifest V2; superseded by Cookie AutoDelete V3, which is listed. |
| Simple Tab Groups | Firefox-only; no Chrome version exists. |
| WhatRuns | Excluded over a May 2026 security-research report that it transmits visited URLs and AI-chatbot conversation content to its servers. |
| Avast Online Security & Privacy | Excluded after its 2019 removal from Mozilla's add-ons store over browsing-history harvesting. |
| Proton Pass | No verifiable official browser-extension repo or license could be located. |
| RescueTime | Legacy MV2 listing was disabled by Chrome; the announced replacement listing could not be confirmed. |

## Related

More awesome-lists in this family:

- [Awesome-terminal](https://github.com/dakotac1994/Awesome-terminal) — terminal emulators and the terminal experience stack.
- [Awesome-diagram-tool](https://github.com/dakotac1994/Awesome-diagram-tool) — diagramming tools: diagram-as-code, whiteboards, ERD, and more.
- [awesome-cli](https://github.com/dakotac1994/awesome-cli) — general CLI/TUI tools.
- [awesome-oss-cli](https://github.com/dakotac1994/awesome-oss-cli) — open-source-only CLI/TUI tools.
- [awesome-oss-macos](https://github.com/Awesome-llms-labs/awesome-oss-macos) — open-source macOS apps.

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first. The short version: suggest extensions that are live on the Chrome Web Store (or officially distributed), work under Manifest V3, and come with a verifiable official source. Every entry needs a working link and a license label — `proprietary` is fine, guessing is not.

## License

This list is released under the [MIT License](LICENSE). Extension names, descriptions, and links belong to their respective owners.
