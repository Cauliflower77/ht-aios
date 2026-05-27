# HT-AIOS / MoveOps v11

Launchable static MVP for moving labor / U-Box dispatch operations.

## What this is

HT-AIOS is currently a single-page static web app designed to support:

- Customer quote and booking flow
- Multi-provider moving operations
- Dispatch and calendar visibility
- Local MVP state management
- Moving labor operations experiments

## Fastest launch path

This repo is suitable for a static deployment on Vercel, Netlify, Cloudflare Pages, or GitHub Pages.

### Vercel settings

- Framework Preset: Other
- Build Command: leave blank
- Output Directory: `.`
- Install Command: leave blank

### Netlify settings

- Build command: leave blank
- Publish directory: `.`

## Current architecture

The app is presently static HTML/CSS/JS. It can launch immediately as a demo/MVP, but production use should add:

- Supabase persistence instead of browser-only storage
- Stripe deposit/payment flow
- Admin authentication
- Provider onboarding controls
- Review request tracking
- Terms of Service and Privacy Policy

## Recommended product direction

Start as an internal Thoroughbred / Central Florida Moving Console before opening as a general public marketplace.

Priority roadmap:

1. Supabase jobs database
2. Admin dispatch dashboard
3. Customer quote/booking form
4. Crew/provider assignment
5. Stripe deposit/payment status
6. Review request tracking
7. Marketplace/provider expansion

## Launch checklist

- [ ] Confirm `index.html` loads correctly
- [ ] Deploy static site
- [ ] Test mobile quote flow
- [ ] Add persistence layer
- [ ] Add payment layer
- [ ] Add legal pages
- [ ] Add review capture workflow

## Environment variables planned

```bash
SUPABASE_URL=
SUPABASE_ANON_KEY=
STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
SENDGRID_API_KEY=
```

Do not commit live secrets to this repo.
