# charity: water — Landing Page

A simple, beginner-friendly landing page based on your Canva design. Built with **HTML + CSS only**, using your brand colors and Proxima Nova.

## 🎨 Brand Settings
- Background: `#1A1A1A`
- Warm brown (promo card): `#BF6C46`
- Yellow (CTA + accents): `#FFC907`
- Font: **Proxima Nova** via CDN

## 📁 Project Structure
```
charity-water-landing-page/
├── index.html
├── style.css
└── assets/
    ├── apple-pay.svg
    ├── google-pay.svg
    ├── samsung-pay.svg
    ├── venmo.svg
    ├── facebook.svg
    ├── x.svg
    ├── instagram.svg
    └── linkedin.svg
```

> Place your official brand mark files in the `assets/` folder with these filenames. PNG works too—keep the same names.

## 🚀 Quick Start (Local)
1. Download & unzip.
2. Open `index.html` in your browser.
3. Add logos to `/assets/` (Apple Pay, Google Pay, Samsung Pay, Venmo, Facebook, X, Instagram, LinkedIn).

## 🌐 Deploy to GitHub Pages
1. Create a new GitHub repo (e.g., `charity-water-landing-page`).
2. Upload all files (including `assets/`).
3. **Settings → Pages**:
   - Build and deployment: `Deploy from a branch`
   - Branch: `main` and `/root`
4. Save. Your site will be at `https://<your-username>.github.io/<repo-name>/` shortly.

### Update Images on GitHub
- In the repo’s `assets/` folder (GitHub UI), **Add file → Upload files**, drop in your SVG/PNG logos using the same filenames.

## 📱 Mobile Menu Notes
- The header includes a **hamburger menu** under 900px (CSS-only, no JS).
- The hamburger animates into an “X” and shows a frosted-glass menu.
- On ≥ 900px, nav shows inline and hamburger hides.
- Edit links inside `<nav id="primary-nav">` in `index.html`.

## 🧩 Customization Tips
- Colors: edit CSS variables in `style.css` under `:root{ ... }`.
- Font: `index.html` links a Proxima Nova CDN—you can self-host if preferred.
- Hero image: replace the placeholder `https://picsum.photos/...` in `index.html`.
- Payment links: set each wallet button `href` to real donation endpoints.
- Social links: update the footer `<a href="#">` URLs.

## ♿ Accessibility
- Accessible labels on CTA and social icons.
- Focus styles preserved.
- Contrast tuned for dark theme.

## 🧪 Checklist
- [ ] Logos placed in `/assets/`
- [ ] Links updated
- [ ] Deployed on GitHub Pages or Netlify
- [ ] Mobile menu toggles on small screens
