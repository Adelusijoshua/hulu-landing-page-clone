
Readme · MD
 
**Front-End Developer · UI Clone Project**
 
🌐 Live site: **[https://huluui-clone.netlify.app/]**
Tech: **HTML5 · CSS3 · Vanilla JavaScript**
 
---
 
## 📌 Overview
 
This is a front-end clone of the **Hulu** streaming platform landing page, built to practice and demonstrate skills in responsive layout design, CSS Grid/Flexbox, and vanilla JavaScript DOM interaction. The site recreates Hulu's hero section, plan bundling promo, content category showcase, live TV/sports sections, and a fully functional login modal built entirely with vanilla HTML, CSS, and JavaScript, no frameworks required.
 
> This is a non commercial clone built for educational and portfolio purposes only. All Hulu branding, imagery, and trademarks belong to their respective owners.
 
---
 
## ✨ Features
 
- **Hero section** — fullbleed background header with logo, CTA button, and gradient overlay for text legibility
- **Login modal** — click to open modal with email & password fields, closes on outside click or close icon, powered by vanilla JS event listeners
- **Plan bundling promo** — sub-header section highlighting Hulu + Disney+ + ESPN+ bundle with call-to-action buttons
- **Category showcase grid** — CSS Grid layout displaying TV Shows, Movies, Hulu Originals, and Premiums with image overlays and gradient shadows
- **Live TV section** — bordered callout panel promoting Hulu + Live TV channels
- **Live sports section** — full-width background section with league logos (NCAA, NBA, NHL, NFL)
- **Responsive footer** — multi-column link directory with social icons
- **Fully responsive** — custom media queries reflow the grid, hero, and modal for mobile and tablet breakpoints
- **Custom typography** — Google Fonts (Rubik) for consistent branding
---
 
## 🗂 Sections
 
| Section | Description |
|---------|-------------|
| **Header/Hero** | Logo, login button, headline copy, and "Start Your Free Trial" CTA over a full-bleed background image |
| **Sub-header** | Bundle promo (Hulu, Disney+, ESPN+) with details and "Get Bundles" CTA |
| **Categories** | Grid of four content categories (TV Shows, Movies, Originals, Premiums) with hover-ready image covers |
| **Live TV** | Bordered highlight panel promoting live channel access |
| **Live Sports** | Background hero panel with league logos and legal disclaimer text |
| **Footer** | Browse, Help, and About Us link columns plus social media icons |
| **Login Modal** | Popup form for email/password login, toggled via JavaScript |
 
---
 
## 🗂 Project Structure
 
```
├── index.html          # Page markup and structure
├── style.css            # All styling, layout, and responsive rules
├── Main.js               # Modal open/close logic and outside-click handling
├── img/                    # Logos, background images, category covers, icons
└── README.md                # Project documentation (this file)
```
 
> Note: `index.html` references assets via `img/`, `style.css`, and `Main.js` — keep this folder structure intact when uploading so all paths resolve correctly.
 
---
 
## 🚀 Getting Started
 
This is a static site with no build tools or dependencies required.
 
1. Clone this repository
2. Open `index.html` directly in a browser, **or** serve it locally:
```bash
   # Using Python
   python -m http.server 8000
 
   # Using Node (npx)
   npx serve .
```
3. Visit `http://localhost:8000`
---
 
## 🛠 Tools & Skills Used
 
- **HTML5** — semantic structure
- **CSS3** — Grid/Flexbox layouts, gradients, custom media queries for responsive design
- **Vanilla JavaScript** — DOM event listeners for modal open/close and outside-click detection
- **Google Fonts** — Rubik
---
 
*Turning Design into Code 🎬*
