# AJANDO.COM — Website Codebase

## Project Structure

```
ajando-website/
├── index.html                  ← Landing page (main)
├── README.md                   ← This file
├── assets/                     ← Put Molly's photos here
│   └── molly-hero.jpg          ← Hero photo (replace placeholder)
└── pages/
    ├── film-video.html         ← Film & Video world
    ├── health-fitness.html     ← Health & Fitness world
    ├── fashion-beauty.html     ← Fashion & Beauty world
    ├── books-stories.html      ← Books & Stories world
    └── mental-health.html      ← Mental Health world (coming soon)
```

## How to Use

1. Open `index.html` in a browser to view the landing page
2. Each world page is in the `pages/` folder
3. All pages are self-contained HTML files — no build tools needed
4. Just open in any browser or upload to any static hosting (Netlify, Vercel, GitHub Pages)

## To Do Before Launch

### Photos
- Replace hero photo placeholder in `index.html` (search for "molly-hero.jpg")
- Add cover images for each content card
- Save all images to the `assets/` folder

### Content
- Fill in Molly's About bio in `index.html` (search for "Molly's full bio")
- Update social media links in footer (Instagram, TikTok, YouTube, Substack)
- Add real prices to Fashion & Beauty shop cards
- Add real product names and images to shop sections

### Mental Health Page
- Final page (mental-health.html) to be completed — full code coming

## Design System

| Variable | Value | Usage |
|----------|-------|-------|
| --black | #0a0807 | Page background |
| --rose | #c9a0a0 | Accent / headings |
| --rose-deep | #a07070 | Buttons / CTAs |
| --choco | #6b3f2a | Warm accents |
| --cream | #f5ede8 | Body text |
| --text-dim | #9a8880 | Muted text |

### Page Accent Colours
- Film & Video: `--rose-deep` (#a07070)
- Health & Fitness: `--green-mid` (#6a7f52)
- Fashion & Beauty: `--gold` (#c8a96e)
- Books & Stories: `--ink` (#7a9a8a)
- Mental Health: soft rose + lavender

## Fonts
All pages use Google Fonts:
- **Playfair Display** — headings, display text
- **Cormorant Garamond** — italic body, quotes
- **Montserrat** — UI, labels, navigation

## Hosting Recommendation
Upload the entire `ajando-website/` folder to:
- **Netlify** (drag & drop deploy — free)
- **Vercel** (free static hosting)
- **GitHub Pages** (free)

Then point your domain `ajando.com` to the hosting provider.
