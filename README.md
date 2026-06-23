# UM Agency Website
**Live URL:** https://agency.ukashamart.com

## Files
- `index.html` — Full website (single file, all CSS + JS inside)
- `vercel.json` — Vercel deployment config

---

## Deploy to Vercel (Step by Step)

### Method 1 — Vercel Dashboard (Easiest)
1. Go to [vercel.com](https://vercel.com) → Login
2. Click **"Add New Project"**
3. Click **"Upload"** (drag & drop the `um-agency` folder)
4. Click **Deploy** → Wait 30 seconds
5. Project is live on a `.vercel.app` URL

### Method 2 — GitHub + Vercel (Recommended)
1. Create a new GitHub repo (e.g. `um-agency`)
2. Upload both files (`index.html` + `vercel.json`)
3. Go to [vercel.com](https://vercel.com) → **Add New Project**
4. Import your GitHub repo
5. Click **Deploy**

---

## Add Custom Domain: agency.ukashamart.com

After deploying on Vercel:

1. Go to your project → **Settings → Domains**
2. Type `agency.ukashamart.com` → Click **Add**
3. Vercel will show you a **CNAME record**:
   - **Name:** `agency`
   - **Value:** `cname.vercel-dns.com`
4. Go to **Cloudflare** (where ukashamart.com DNS is managed)
5. DNS → Add Record:
   - Type: `CNAME`
   - Name: `agency`
   - Target: `cname.vercel-dns.com`
   - Proxy: **OFF (DNS only)** ← important
6. Wait 2–5 minutes → Done ✅

---

## To Add New Guest Posting Sites
Open `index.html` → Find `id="gp-container"` → Copy any `.gp` card and paste with new data.

## Contact Info
- WhatsApp 1: +92 335 1650895
- WhatsApp 2: +92 347 7350040
- Email: agency@ukashamart.com
- CEO: ukashaceo@gmail.com
