# LaunchHype

> **Hype up your launch in 30 seconds.**

Paste your product URL → get a complete launch kit with platform-specific posts + visual assets. Stop spending 3 hours writing launch posts. Let AI do it.

🌐 [launchhype.site](https://launchhype.site)

---

## The Problem

Vibe coding made building products easy. But getting users? Still painfully hard.

Makers struggle to write engaging posts for 6+ platforms, create visual assets, and understand each platform's unwritten rules. **Great products die in silence.**

## The Solution

Paste your product URL → get **everything you need** to launch:

### 📝 AI Launch Posts (6 Platforms)
| Platform | What You Get |
|----------|-------------|
| Product Hunt | Tagline, description, first comment |
| X / Twitter | Launch thread (5-7 tweets) |
| LinkedIn | Professional announcement |
| Reddit | Authentic post + best subreddit suggestions |
| Hacker News | Show HN title + description |
| Indie Hackers | Community-style story post |

### 🎨 Visual Assets
- **Social Cards** — OG images for sharing on X & LinkedIn
- **Product Hunt Thumbnails** — Correctly sized gallery images
- **Feature Cards** — For X threads & LinkedIn carousels
- **Device Mockups** — Screenshot in laptop/phone frame

### ⚡ One-Click Everything
- Copy any post to clipboard
- Download individual images or full kit as ZIP
- Track which platforms you've posted to

---

## Pricing

| | **Free** | **Starter ($9/mo)** | **Pro ($29/mo)** |
|---|---------|-------------------|-----------------|
| Products | 1 only | 5/month | Unlimited |
| Text posts | All 6 platforms | All 6 platforms | All 6 platforms |
| Visual assets | ❌ None | 1 social card/launch | Full kit (all types) |
| Brand voice | ❌ | ❌ | ✅ Custom |
| A/B variants | ❌ | ❌ | ✅ |
| Watermark | "Made with LaunchHype" | Removed | Removed |

---

## Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Styling:** Vanilla CSS
- **AI:** OpenAI GPT-4o
- **Image Generation:** Satori + Puppeteer (template-based)
- **Auth:** NextAuth.js / Clerk
- **Database:** Supabase (PostgreSQL)
- **Payments:** Stripe
- **Hosting:** Vercel

---

## Getting Started

```bash
git clone https://github.com/yourusername/launchhype.git
cd launchhype
npm install
cp .env.example .env.local
# Add your API keys (OpenAI, Supabase, Stripe)
npm run dev
```

Visit `http://localhost:3000`

## Environment Variables

```
OPENAI_API_KEY=your_openai_key
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
STRIPE_SECRET_KEY=your_stripe_secret
STRIPE_PRICE_PRO=your_pro_price_id
STRIPE_PRICE_LIFETIME=your_lifetime_price_id
NEXTAUTH_SECRET=your_random_secret
```

---

## Roadmap

- [x] AI launch post generator (6 platforms)
- [x] Template-based visual asset generator
- [x] One-click copy & download
- [ ] Custom brand voice (Pro)
- [ ] A/B post variants
- [ ] Launch scheduling & reminders
- [ ] Weekly post suggestions
- [ ] API access
- [ ] Team plans

---

## Vision

> **Cursor is for vibe coding. LaunchHype is for vibe marketing.**

Vibe coding is here. Vibe marketing is next. LaunchHype is the bridge.

---

## License

MIT

---

Built with ❤️ by a solo maker who was tired of staring at blank post editors after shipping.
