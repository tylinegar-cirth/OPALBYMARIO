# Opal By Mario - Website

Luxury website for Mario Ikasovic's Australian opal business.

## Quick Deploy to Vercel (Recommended)

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create account)
2. Click the **+** icon → **New repository**
3. Name it `opalbymario-site`
4. Keep it **Public** or **Private** (either works)
5. Click **Create repository**

### Step 2: Upload Files
1. On your new repo page, click **"uploading an existing file"**
2. Drag and drop ALL files/folders from this package:
   - `package.json`
   - `public/` folder
   - `src/` folder
3. Click **Commit changes**

### Step 3: Deploy on Vercel
1. Go to [vercel.com](https://vercel.com)
2. Sign up/login with your GitHub account
3. Click **"Add New..."** → **"Project"**
4. Find and select your `opalbymario-site` repository
5. Click **Deploy** (keep all default settings)
6. Wait ~2 minutes for build to complete
7. Your site is live! 🎉

### Step 4: Connect Custom Domain (opalbymario.com)
1. In Vercel, go to your project → **Settings** → **Domains**
2. Add `opalbymario.com`
3. Vercel will show you DNS records to add
4. Go to your domain registrar (where you bought the domain)
5. Add the DNS records Vercel provides
6. Wait 5-30 minutes for DNS to propagate
7. Done! Your site is now at opalbymario.com

---

## Local Development (Optional)

If you want to run locally:

```bash
npm install
npm start
```

Opens at http://localhost:3000

---

## File Structure

```
opalbymario-site/
├── package.json          # Dependencies
├── public/
│   └── index.html        # HTML template with SEO tags
├── src/
│   ├── index.js          # React entry point
│   └── OpalByMario.js    # Main website component
└── README.md             # This file
```

---

## Need Help?

- Vercel Docs: https://vercel.com/docs
- Domain Setup: https://vercel.com/docs/projects/domains

Built with ❤️ for Opal By Mario
