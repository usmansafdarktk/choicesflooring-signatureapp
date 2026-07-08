# Choices Flooring Mackay — Email Signature Generator

A single-page web app that generates brand-consistent email signatures for
Choices Flooring Mackay staff. Enter a staff member's details, preview the
signature live, then copy it or download it as an image.

**Live app:** https://usmansafdarktk.github.io/choicesflooring-signatureapp/

## Features

- Live preview that updates as you type
- Branded illustration, uploaded staff photo, or initials for the profile image
- **Copy signature** — pastes with clickable links into Gmail, Apple Mail and classic Outlook
- **Download image (PNG)** — for *new Outlook*, insert via **Insert → Pictures** (always keeps the full design)
- **Download .html** / **Copy HTML source** for admins
- Fully self-contained — the logo, icons and watermark are embedded, so nothing needs hosting

## Installing a signature

**New Outlook:** Download image (PNG) → in the signature editor go to
**Insert → Pictures** → choose the file → name it → Save.

**Gmail / Apple Mail / classic Outlook:** click **Copy signature**, then paste
(⌘V / Ctrl+V) into the signature box (keeps links clickable).

## Development

The app is a single file, `index.html`. All assets are inlined as base64, so
it works offline — just open it in a browser. `Signature Generator.html` is an
identical copy kept for convenient local use. Source brand assets live in the
`email signature/` folder.
