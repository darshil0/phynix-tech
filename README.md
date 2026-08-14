# Phynix Tech Services — Enterprise Web, QA & IT Infrastructure Site

This repository contains the multi-page static web architecture for **Phynix Tech Services** (Headquartered in Dallas, TX). The site showcases the company's expansion into Enterprise Web Design & Development, Quality Assurance (QA) Engineering, Managed Cloud Operations, and Industrial IT Infrastructure.

---

## 🏛️ Architecture & Core Principles

- **Architecture:** Multi-Page Application (MPA) consisting of standalone HTML5 pages.
- **Styling Engine:** Utility-first CSS using [Tailwind CSS](https://tailwindcss.com/).
- **Zero-JavaScript Mandate:** Built strictly using native HTML5 and CSS. No dynamic JavaScript scripts, client-side routing, or external runtime libraries are included, ensuring maximum performance, zero client-side script security vectors, and fast edge delivery.
- **Accessibility:** Structured using semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) following WCAG 2.1 AA accessibility standards.

---

## 📁 Repository Directory Structure

```text
phynixtech-site/
├── .nojekyll              # Forces GitHub Pages to serve raw static files (bypasses Jekyll)
├── README.md              # Project documentation
├── index.html             # Main Landing Page & Capabilities Summary
├── web-services.html      # UI/UX Design & Full-Stack Web Development
├── qa-testing.html        # Quality Engineering & Automated Test Frameworks
├── infrastructure.html    # Cloud Operations, OT & Cybersecurity Hardening
└── contact.html           # Direct Contact Info & Native HTML5 Form

```

---

## 🚀 Local Development & Preview

Since this repository uses pure HTML and CSS, no build scripts, node packages, or server runtimes are required.

### Option 1: Direct File Access

Open `index.html` directly in any web browser.

### Option 2: Local HTTP Server (Recommended)

To test absolute pathing and local routing:

```bash
# Using Python 3 built-in HTTP server
python -m http.server 8000

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
* Ensure a `CNAME` file containing your domain (e.g., `phynixtechservice.com`) is placed in the root folder.
* Configure DNS `A` records to point to GitHub Pages IP addresses (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`).



---

## 📄 Corporate Information

**Phynix Tech Services**

111 W Mockingbird Ln, Dallas, TX 75247, USA

*Core Offerings:* Web Design & Development | QA & Automation | Managed Cloud | OT & Industrial IT Infrastructure

```

```
