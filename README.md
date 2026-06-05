# CTD Africa — Official Website
**ctd-africa.com** · Connect The Dots Africa · Pretean (Pty) Ltd

---

## Deploy to Cloudflare Pages (via GitHub)

1. Push this entire `ctd-africa` folder to a new GitHub repository (can be private)
2. Go to [Cloudflare Dashboard](https://dash.cloudflare.com) → **Pages** → **Create a project** → **Connect to Git**
3. Select the repository
4. Build settings:
   - Framework preset: **None**
   - Build command: *(leave blank)*
   - Build output directory: **`/`** (root)
5. Click **Save and Deploy**
6. Add `ctd-africa.com` under **Custom Domains**

---

## File Structure

```
ctd-africa/
├── index.html      ← Full site (self-contained)
├── 404.html        ← Custom 404 page
├── sitemap.xml     ← XML sitemap for Google
├── robots.txt      ← Crawler rules
├── _redirects      ← Cloudflare routing
├── _headers        ← Security & cache headers
└── README.md       ← This file
```

---

## After Deploy — SEO Checklist

- [ ] Submit `https://ctd-africa.com/sitemap.xml` to [Google Search Console](https://search.google.com/search-console)
- [ ] Submit to [Bing Webmaster Tools](https://www.bing.com/webmasters)
- [ ] Create a [Google Business Profile](https://business.google.com) — critical for SA local search
- [ ] Create `og-image.jpg` (1200×630px) and upload to root for WhatsApp/LinkedIn share previews

---

## Contact

info@ctd-africa.com · @CTD_Africa · @ctd_africa
WhatsApp: +27 81 770 1493
191 Leeuwport Street, Boksburg, Gauteng 1460
