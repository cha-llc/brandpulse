# 🟡 BrandPulse — AI Brand Audit Tool

**"Does your brand actually work?"**

BrandPulse is a fully automated $47 brand audit tool. Answer 15 questions, get a 12-page forensic analysis of your brand across 6 dimensions with a priority fix roadmap — delivered instantly.

## What It Does
- Scores your brand across 6 dimensions: Clarity, Trust, Emotion, Positioning, Visibility, Conversion
- Generates a personalized priority fix roadmap
- Delivers a 12-page PDF report via email
- 100% automated — no human involvement after setup

## Tech Stack
- Pure HTML/CSS/JS — single file, zero dependencies
- Stripe Payment Links for checkout ($47 one-time)
- Gmail/Systeme.io for automated report delivery
- Supabase (optional) for customer records

## Setup
1. Open `index.html`
2. Replace the Stripe comment with your Payment Link:
   ```js
   window.location.href = 'https://buy.stripe.com/YOUR_LINK';
   ```
3. Deploy to Netlify Drop, Vercel, or any static host
4. Connect Stripe webhook → Gmail for report delivery

## Pricing
- **$47 one-time** per audit
- Target: small business owners, consultants, coaches

## License
© 2026 C.H.A. LLC — All rights reserved
