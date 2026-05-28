# IPTV Sky Glass — Vercel Deployment

## 🚀 Deploy to Vercel in 3 Steps

### Method 1: Vercel Dashboard (Easiest)
1. Go to https://vercel.com and sign in
2. Click **"Add New Project"** → **"Upload"**
3. Drag and drop this entire folder → click **Deploy**
4. After deploy, go to **Settings → Domains**
5. Add your domain: `www.iptvskyglass.com`

### Method 2: Vercel CLI
```bash
npm install -g vercel
cd iptv-sky-glass
vercel --prod
```

## 📁 Project Structure
```
iptv-sky-glass/
├── index.html              ← Homepage (Sky Glass Iptv menu)
├── installation-guide.html ← Installation Guide menu page  
├── buy-now.html            ← Buy Now / Pricing menu page
├── reseller-panel.html     ← Reseller Panel menu page
├── blog.html               ← Blog menu page
├── vercel.json             ← Routing config (DO NOT DELETE)
├── robots.txt              ← SEO
├── sitemap.xml             ← SEO sitemap
├── images/                 ← All 94 images
├── css/                    ← All stylesheets
├── js/                     ← All scripts
└── fonts/                  ← All fonts
```

## 🌐 Domain Setup
After deploy, set your custom domain in Vercel:
- Primary: `www.iptvskyglass.com`
- Redirect: `iptvskyglass.com` → `www.iptvskyglass.com`

## 📞 Contact Info (already in site)
- WhatsApp: +447525 577857
- Email: iskyglass@gmail.com
