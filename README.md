# 🌿 ReverseAge — Biological Age Tracker

A beautiful, fully-featured web application for tracking and reversing your biological age through daily habit monitoring. **100% free, no backend, no data collection — everything runs in the user's browser.**

## 🚀 Deploy to Vercel

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) and click **"New Project"**
3. Import your GitHub repository
4. Click **Deploy** — that's it!

## 📋 Features

- **Aging Speed Assessment** — 20-question initial survey scoring 7 lifestyle categories
- **Daily Check-In Tracker** — 15-question daily habit log (~5 minutes)
- **Animated Score Circles** — Visual aging speed score with color-coded feedback
- **Personalized Feedback** — Category-specific advice on strengths and areas to improve
- **14-Day Trend Chart** — Line chart showing your aging speed over time (Chart.js)
- **Weekly / Monthly / Annual Reports** — Tabbed report views with category breakdowns
- **Areas to Work On** — Smart analysis of your worst 30-day patterns with action tips
- **300 Rotating Quotes** — Daily motivational quote (changes every 24h)
- **60 Health Facts** — Science facts that rotate every 3 hours
- **Mobile-Responsive** — Fully optimized for all screen sizes with bottom tab nav
- **Ad Placeholders** — Pre-placed on every view for Google AdSense
- **SEO Optimized** — 2,500+ word article, full meta tags, Open Graph, JSON-LD structured data
- **Analytics Ready** — Google Analytics GA4 placeholder in `<head>` (just uncomment)
- **AdSense Ready** — Google AdSense script placeholder (just uncomment)
- **Search Console Ready** — Verification meta tag placeholder

## ⚙️ Setup After Deploying

### Google Analytics
1. Create a GA4 property at [analytics.google.com](https://analytics.google.com)
2. Copy your Measurement ID (format: `G-XXXXXXXXXX`)
3. Uncomment the Analytics block in `index.html` and replace `G-XXXXXXXXXX`

### Google AdSense
1. Apply at [adsense.google.com](https://adsense.google.com)
2. Once approved, uncomment the AdSense script in `index.html`
3. Replace `ca-pub-XXXXXXXXXXXXXXXX` with your Publisher ID
4. Replace the ad placeholder divs with your actual ad units

### Google Search Console
1. Go to [search.google.com/search-console](https://search.google.com/search-console)
2. Add your domain and choose **HTML tag** verification method
3. Copy your verification code and replace `YOUR_VERIFICATION_CODE_HERE` in `index.html`
4. Update the `sitemap.xml` URL to match your actual domain

### Custom Domain
1. In Vercel dashboard → your project → Settings → Domains
2. Add your custom domain and follow the DNS instructions

## 🔒 Privacy
All user data is stored exclusively in `localStorage` in the user's own browser. No server, no database, no tracking. Zero data is ever transmitted or stored remotely.

## 📁 File Structure
```
reverseage/
├── index.html      — All views, SEO content, ad placeholders
├── style.css       — Complete design system (Vitality Garden theme)
├── app.js          — All data, logic, routing, rendering
├── vercel.json     — Vercel deployment config with security headers
├── robots.txt      — Search engine crawl permissions
├── sitemap.xml     — XML sitemap for SEO
└── README.md       — This file
```
