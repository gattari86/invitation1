# Deployment Guide - Caribbean Wedding Website Template

## ✅ Project Status

Your luxury wedding invitation **template** is complete and ready to deploy as a portfolio example!

## 📦 What's Been Built

✨ **Custom Luxury Design**
- Color palette extracted from your sample assets (sage green, coral, burgundy, tan, beige)
- Responsive layout that looks beautiful on all devices
- Professional typography with Cormorant Garamond & Montserrat fonts

🎬 **Micro-Animations**
- Smooth fade-in effects on scroll
- Floating elements and hover interactions
- Shimmer and pulse animations
- Parallax hero section

🎵 **Interactive Features**
- Background music player with controls
- Live countdown timer to March 7, 2026
- Smooth scroll navigation
- Image galleries with hover effects

📱 **All Sections Complete**
- Hero with Jane & Joe names
- Welcome message about Caribbean destination wedding
- Countdown timer to July 12, 2026
- Event timeline (Ceremony, Cocktails, Reception)
- Sandals Royal Caribbean resort gallery
- Couple photo gallery
- Attire guide for tropical beach wedding
- RSVP email integration
- Footer with hashtag #JaneAndJoeInParadise

## 🚀 Deployment Options

### Option 1: Deploy to Vercel (Recommended)

**Step 1: Login to GitHub CLI**
```bash
gh auth login
```
Follow the prompts to authenticate with your GitHub account.

**Step 2: Create GitHub Repository**
```bash
cd ~/wedding-invitation-claudia-jeremy
gh repo create caribbean-wedding-template --public --source=. --remote=origin --description="Luxury Caribbean wedding website template - Jane & Joe example"
```

**Step 3: Push to GitHub**
```bash
git push -u origin main
```

**Step 4: Deploy to Vercel**
1. Visit [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Import Project"
4. Select your `caribbean-wedding-template` repository
5. Click "Deploy"
6. Done! Your template site will be live at `caribbean-wedding-template.vercel.app`

**Step 5: Add Custom Domain (Optional)**
1. In Vercel dashboard, go to your project settings
2. Click "Domains"
3. Add your preferred custom domain
4. Follow Vercel's instructions to update DNS records

---

### Option 2: Deploy to Netlify

**Step 1: Create GitHub Repository**
```bash
cd ~/wedding-invitation-claudia-jeremy
gh auth login  # If not already logged in
gh repo create wedding-invitation-huddleson2026 --public --source=. --remote=origin
git push -u origin main
```

**Step 2: Deploy to Netlify**
1. Visit [netlify.com](https://netlify.com)
2. Sign in and click "Add new site" → "Import an existing project"
3. Connect to GitHub and select `wedding-invitation-huddleson2026`
4. Click "Deploy site"
5. Your site will be live at a Netlify URL

**Or use drag-and-drop:**
1. Visit [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `wedding-invitation-claudia-jeremy` folder
3. Done! Instant deployment

---

### Option 3: Manual GitHub Pages

**Step 1: Push to GitHub**
```bash
cd ~/wedding-invitation-claudia-jeremy
gh auth login
gh repo create wedding-invitation-huddleson2026 --public --source=. --remote=origin
git push -u origin main
```

**Step 2: Enable GitHub Pages**
1. Go to your repository on GitHub
2. Click "Settings" → "Pages"
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be live at `yourusername.github.io/wedding-invitation-huddleson2026`

---

## 🧪 Testing Locally

Your invitation is already viewable in your browser! To test again:

```bash
cd ~/wedding-invitation-claudia-jeremy
open index.html
```

Or use a simple local server:
```bash
cd ~/wedding-invitation-claudia-jeremy
python3 -m http.server 8000
# Visit http://localhost:8000
```

---

## 📁 Project Location

All files are in: `~/wedding-invitation-claudia-jeremy/`

## 🎨 Key Features Implemented

1. ✅ Luxury color palette from sample assets
2. ✅ Micro-animations throughout
3. ✅ Background music with player controls
4. ✅ Live countdown timer
5. ✅ Photo galleries (resort & couple)
6. ✅ Event details (ceremony, cocktails, reception)
7. ✅ Attire guide with image
8. ✅ RSVP button integration
9. ✅ Fully responsive design
10. ✅ Social media meta tags
11. ✅ AOS scroll animations
12. ✅ Hover effects on all interactive elements

---

## 🛠️ Customization Tips

If you need to make any changes later:

**Update Colors**: Edit CSS variables in `index.html` around line 30
**Change Text**: Search for specific text in `index.html` and replace
**Replace Images**: Replace files in `assets/images/` folders
**Update Music**: Replace `assets/audio/background-music.mp3`
**Change Date**: Update `const weddingDate` in the JavaScript section

---

## 📞 Next Steps

1. **Authenticate with GitHub**: Run `gh auth login`
2. **Choose deployment method** (Vercel recommended)
3. **Push and deploy**
4. **Share the link** with Jeremy & Claudia!
5. **Optional**: Set up custom domain (huddleson2026.com)

---

## ✨ What Makes This Special

- **Professional Grade**: Uses industry-standard tools (AOS, Phosphor Icons, Animate.css)
- **Performance Optimized**: Fast loading, smooth animations
- **Mobile-First**: Looks stunning on phones, tablets, and desktops
- **Accessibility**: Semantic HTML, proper contrast ratios
- **SEO Ready**: Meta tags for social sharing
- **No Build Required**: Pure HTML/CSS/JS - works everywhere

---

**Ready to go live!** 🎉

Just run `gh auth login` and follow the deployment steps above.
