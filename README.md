# Urbandrobe — Dress the Culture

> Curated men's fashion — Streetwear, Ethnic & Festive, Smart Casuals from Amazon India.

## 🚀 Quick Start

1. Clone this repository
2. Deploy to GitHub Pages or Netlify
3. Configure Decap CMS authentication (see below)
4. Start adding products!

## 📁 Structure

```
urbandrobe/
├── index.html              ← Homepage
├── streetwear.html          ← Category page
├── ethnic.html              ← Category page
├── smart-casuals.html       ← Category page
├── style-guide.html         ← Blog/editorial index
├── admin/                   ← Decap CMS admin panel
│   ├── index.html
│   └── config.yml
├── _products/               ← Product markdown files (CMS-managed)
├── _posts/                  ← Blog post markdown files (CMS-managed)
├── products/                ← Individual product pages
├── css/                     ← Stylesheets
├── js/                      ← JavaScript
├── images/                  ← All images
├── sitemap.xml              ← SEO sitemap
├── robots.txt               ← Crawler rules
└── _config.yml              ← GitHub Pages config
```

## 🎨 Tech Stack

- **Frontend:** Pure HTML + CSS + Vanilla JS (no frameworks)
- **CMS:** Decap CMS (free, git-based)
- **Hosting:** GitHub Pages (free)
- **Auth:** Netlify Identity (free tier)
- **Monetisation:** Amazon Associates affiliate links

## 🔧 Setup

### 1. GitHub Pages
- Push this repo to GitHub
- Go to Settings → Pages → Source: main branch
- Your site will be live at `https://username.github.io/urbandrobe`

### 2. Custom Domain
- Purchase `urbandrobe.in` or `urbandrobe.com`
- Add CNAME record pointing to `username.github.io`
- Update `_config.yml` with your domain

### 3. Decap CMS + Netlify Identity
- Deploy the same repo on Netlify (free tier)
- Enable Netlify Identity in site settings
- Enable Git Gateway in Identity settings
- Invite yourself as a user
- Go to `yoursite.com/admin/` to manage content

### 4. Amazon Associates
- Sign up for Amazon Associates (India)
- Replace `tag=urbandrobe-21` in all affiliate links with your tag
- Update sample products with real Amazon product links

## 📝 Content Management

Access the admin panel at `/admin/` to:
- **Add/Edit/Delete Products** — Fill in name, category, price, image, description, and Amazon link
- **Publish Style Guide Posts** — Write fashion content targeting SEO keywords
- **Toggle Featured Products** — Mark products to appear on the homepage

## 📌 Pinterest Strategy

1. Create vertical (4:5) product pins with your branding
2. Link pins to category or product pages
3. Use keyword-rich descriptions
4. Post 5-10 pins daily across boards
5. Drive traffic: Pinterest → Urbandrobe → Amazon → Commission

## 📄 License

© 2025 Urbandrobe. All rights reserved.
