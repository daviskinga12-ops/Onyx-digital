# Security Policy — Onyx Digital Platform

## What data this tool stores

Onyx Digital Platform stores the following data **locally in your browser only** (localStorage):

- Your Gemini API key
- Your client list (names, contacts, packages, fees)
- Usage stats (posts generated, briefs made)

**None of this data is sent to any server owned by Onyx Digital Platform.** It never leaves your device except for direct API calls to Google's Gemini API for AI generation.

## API Key Security

- Your Gemini API key is stored in your browser's localStorage
- It is only ever sent directly to `generativelanguage.googleapis.com` (Google's official API)
- It is never logged, shared, or transmitted anywhere else
- If you use a shared or public device, click ⚙ AI Key and clear your key after use

## Reporting a vulnerability

If you discover a security issue in this tool, contact the owner directly via the contact details in your client agreement. Do not publicly disclose any vulnerability before it has been addressed.

## Recommendations for users

- Use this tool on a private, personal device only
- Do not share your deployed Vercel URL publicly — it is an internal business tool
- Rotate your Gemini API key periodically at aistudio.google.com
- Do not store client passwords inside this tool — use Meta Business Suite, TikTok Business Center, and YouTube Studio for access management

## Third-party services

This tool connects to:

| Service | Purpose | Data sent |
|---|---|---|
| Google Gemini API | AI content generation | Your prompt text only |
| Google Fonts | Typography | None (CSS only) |
| Vercel | Hosting | None (static file only) |

---

Onyx Digital Platform © 2026
