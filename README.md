# Hosting Legal Docs on GitHub Pages

## Quick Setup (5 minutes)

### 1. Create GitHub Repository

```bash
cd /Users/nathanhubert/Desktop/lil-taps-ultimate/legal-hosting
git init
git add .
git commit -m "Initial legal docs"
```

### 2. Push to GitHub

1. Go to https://github.com/new
2. Create repo named `liltaps` (public)
3. Run:

```bash
git remote add origin https://github.com/YOUR-USERNAME/liltaps.git
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to repo Settings → Pages
2. Source: `main` branch, `/` (root)
3. Click Save
4. Wait 2 minutes

### 4. Your URLs

- **Privacy**: `https://YOUR-USERNAME.github.io/liltaps/privacy.html`
- **Terms**: `https://YOUR-USERNAME.github.io/liltaps/terms.html`

### 5. Update App Store Connect

When creating your app listing, paste these URLs into:
- **Privacy Policy URL**: your privacy.html link
- **Terms of Use URL**: (optional, but good to include)

---

## Files Included

- `privacy.html` - COPPA compliant, no data collection
- `terms.html` - Subscription pricing, refunds, usage rights

Both styled to match your app's color scheme (#FFF9E8 cream, #FF8A7A coral, #6ECFCF teal).

---

## Updating Later

To update these pages:

```bash
cd /Users/nathanhubert/Desktop/lil-taps-ultimate/legal-hosting
# Edit privacy.html or terms.html
git add .
git commit -m "Update privacy policy"
git push
```

Changes go live in ~2 minutes automatically.
