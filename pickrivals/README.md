# PickRivals.com

AI Tools & SaaS Comparison/Deals website built with Astro + Tailwind CSS.

## 🚀 Quick Start

```bash
npm install
npm run dev
```

## 📦 Deploy to Netlify

1. Push this folder to a GitHub repo
2. Go to [netlify.com](https://netlify.com) → "Add new site" → "Import from Git"
3. Select your repo
4. Build command: `npm run build`
5. Publish directory: `dist`
6. Connect your custom domain: pickrivals.com

## 📝 Adding New Articles

Create a new `.astro` file in `src/pages/blog/your-article-slug.astro` following the template in `best-ai-writing-tools-2026.astro`.

## 💌 Newsletter Setup (Beehiiv)

1. Sign up at [beehiiv.com](https://beehiiv.com)
2. Create your publication
3. Go to Settings → Embed → Copy your embed code
4. Replace the placeholder forms in:
   - `src/components/NewsletterSignup.astro`
   - `src/pages/newsletter.astro`

## 🔗 Affiliate Links

Replace all `#tool-affiliate` placeholders in the deal cards and articles with your real affiliate URLs from:
- [PartnerStack](https://partnerstack.com) — most SaaS tools
- [Impact.com](https://impact.com) — large brands
- [Amazon Associates](https://affiliate-program.amazon.com) — hardware/books

## 📁 Project Structure

```
src/
├── components/       # Nav, Footer, DealCard, NewsletterSignup
├── layouts/          # Main Layout.astro with SEO meta
├── pages/
│   ├── index.astro   # Homepage
│   ├── deals.astro   # Deals page
│   ├── newsletter.astro
│   ├── blog/         # Blog articles
│   └── compare/      # Tool comparisons
└── public/           # Static assets
```
