# Changelog — Onyx Digital Platform

All notable changes to this project are documented here.
Format: `[version] — date — what changed`

---

## [1.2.0] — April 2026

### Added
- **Algorithm tab** — 5 new AI tools for hooking platform algorithms:
  - Hook Strength Tester (scores + rewrites post opening lines)
  - Algorithm Audit (scores full post on every platform signal)
  - 7-Day Story Sequence Generator
  - Optimal Posting Schedule Generator
  - DM Funnel Script Generator (converts followers into buyers)
- `robots.txt` — blocks search engine indexing (private tool)
- `manifest.json` — app installable on mobile as PWA
- `SECURITY.md` — security policy
- `PRIVACY.md` — client-facing privacy policy
- `CHANGELOG.md` — this file

### Fixed
- Mobile navigation overflow with 8 tabs (now horizontally scrollable)
- Favicon added (was missing — browser tab showed blank)
- Meta description and Open Graph tags added to HTML head

---

## [1.1.0] — March 2026

### Added
- **Optimize tab** — Caption Optimizer, Bio Optimizer, Engagement Script Generator
- **Repurpose tab** — Cross-Platform Repurposer, Hashtag Set Generator
- `vercel.json` — deployment config with 5 security headers
- `.gitignore` — prevents secrets and OS files from reaching GitHub
- `README.md` — project documentation
- `LICENSE` — proprietary usage rights

### Changed
- AI engine switched from Anthropic Claude API (paid) to Google Gemini API (free)
- API key gate updated for Gemini key format (AIza...)
- All references to Anthropic/Claude removed from UI

---

## [1.0.0] — March 2026 — Initial build

### Features
- Home dashboard with live client stats
- Content Generator — 30 AI posts with CSV export for Buffer
- Ad Brief Generator — campaign briefs for Meta, TikTok, Google
- Client Tracker — roster, packages, revenue, renewal dates
- SOP Guide — 8-step operating procedure + monthly report generator
- API key gate (local storage only)
- Fully responsive design
