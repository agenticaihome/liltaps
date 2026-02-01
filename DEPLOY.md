# 🚀 Quick GitHub Pages Deployment

## Step 1: Create GitHub Repo

1. Go to https://github.com/new
2. **Repository name:** `liltaps`
3. **Visibility:** Public ✅
4. **Do NOT** initialize with README
5. Click **Create repository**

## Step 2: Push This Folder

Copy your GitHub username, then run:

```bash
cd /Users/nathanhubert/Desktop/lil-taps-ultimate/legal-hosting

# Replace YOUR-USERNAME with your actual GitHub username
git remote add origin https://github.com/YOUR-USERNAME/liltaps.git
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repo: `https://github.com/YOUR-USERNAME/liltaps`
2. Click **Settings** tab
3. Scroll to **Pages** (in left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 2 minutes

## Step 4: Get Your URLs

After 2 minutes, your pages will be live at:

- **Privacy:** `https://YOUR-USERNAME.github.io/liltaps/privacy.html`
- **Terms:** `https://YOUR-USERNAME.github.io/liltaps/terms.html`
- **Support:** `https://YOUR-USERNAME.github.io/liltaps/support.html`

## Step 5: Verify

Click each URL to make sure they work. You'll use these in App Store Connect!

---

## Next Step

After this works, move to **Step 2** in the submission roadmap: Set up EAS for cloud builds.

✅ Git repo initialized and ready to push!
