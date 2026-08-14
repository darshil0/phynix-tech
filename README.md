# Phynix Tech Services — Enterprise Web, QA & IT Services Offering

This repository contains the multi-page static web architecture for **Phynix Tech Services** (Headquartered in Dallas, TX). The site showcases the company's enterprise offerings across Web Design & Engineering, Quality Assurance (QA) Engineering, Managed Cloud Operations, and Industrial IT Infrastructure.

---

## 🏛️ Architecture & Technical Principles

- **Architecture:** Multi-Page Application (MPA) consisting of standalone HTML5 pages (`index.html`, `web-services.html`, `qa-testing.html`, `infrastructure.html`, `contact.html`).
- **Theme Support:** Native Light & Dark theme toggle powered by Tailwind CSS `dark:` class modifiers and zero-dependency inline theme script preserving system preferences and `localStorage`.
- **Pure Static Architecture:** Built strictly using native HTML5 and utility CSS without heavy JS frameworks, external build dependencies, or client-side routing.
- **Static Corporate Contact:** Replaced dynamic contact forms with a clean static corporate contact section featuring Dallas HQ details, direct email mailto links, and support availability.
- **Accessibility:** Full WCAG 2.1 AA compliance with semantic HTML tags, explicit ARIA attributes, and WCAG-compliant color contrast across both light and dark themes.

---

## 📁 Repository Directory Structure

```text
phynixtech-site/
├── .nojekyll              # Forces GitHub Pages to serve raw static files (bypasses Jekyll)
├── README.md              # Project documentation
├── CHANGELOG.md           # Version release history following Keep a Changelog standards
├── favicon.svg            # Vector flame icon for brand identity
├── index.html             # Main Landing Page & Enterprise Capabilities Summary
├── web-services.html      # Enterprise Web Design, UI/UX & Edge Architecture
├── qa-testing.html        # Quality Engineering & Automated Verification Frameworks
├── infrastructure.html    # Managed Cloud Operations, OT Security & Infrastructure
└── contact.html           # Corporate Contact Details & Operating Hours
```

---

## 🚀 Local Development & Preview

Since this repository uses pure HTML and CSS, no build scripts, node packages, or complex server runtimes are required.

### Option 1: Direct File Access

Open `index.html` directly in any modern web browser.

### Option 2: Local HTTP Server (Recommended)

To test pathing and theme preference persistence across pages:

```bash
# Using Python 3 built-in HTTP server
python3 -m http.server 8000

# Using Node npx serve
npx serve .
```

Then navigate to `http://localhost:8000` in your browser.

---

## 🌐 GitHub Pages Deployment Guide

This repository is optimized for direct hosting on **GitHub Pages**.

1. **Jekyll Bypass:** The `.nojekyll` file in the root directory ensures GitHub Pages serves files as raw static assets without processing them through Jekyll.
2. **Publishing Branch:** Configured to deploy from the `main` branch at `/(root)`.
3. **Custom Domain setup (Optional):**
   - Ensure a `CNAME` file containing your domain (e.g., `phynixtechservice.com`) is placed in the root folder.
   - Configure DNS `A` records to point to GitHub Pages IP addresses (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`).

---

## 📄 Corporate Information

**Phynix Tech Services**

111 W Mockingbird Ln, Dallas, TX 75247, USA

*Direct Email:* [contact@phynixtech.com](mailto:contact@phynixtech.com)

*Core Offerings:* Enterprise Web Services | QA & Automation | Managed Cloud Operations | OT & Industrial IT Infrastructure
