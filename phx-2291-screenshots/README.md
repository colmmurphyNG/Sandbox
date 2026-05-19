# PHX-2291 cross-browser smoke captures

Visual evidence for [ntgrweb/SFCC-webapp PR #1330](https://github.com/ntgrweb/SFCC-webapp/pull/1330) — Firefox + WebKit responsive-image `hideOnMobile` mis-anchoring fix (PHX-2281 follow-up).

Captures of the `/av/` AV_Hero on stage bundle 2980:

- 6 **before** files (`hero-{viewport}-{engine}.png`) — pre-fix, AV_Hero flush-left on Firefox / WebKit at viewport ≥744px
- 6 **after** files (`hero-after-{viewport}-{engine}.png`) — post-fix on local branch build, AV_Hero right-anchored on all 3 engines

Viewports: desktop 1280×800, iPad 1024×768. Engines: Chromium, Firefox, WebKit.

Public web-page renders only; no PII.
