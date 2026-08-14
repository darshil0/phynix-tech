# Changelog

All notable changes to the Phynix Tech Services website project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-03-30

### Added
- **Favicon Integration**: Added vector SVG favicon (`favicon.svg`) featuring custom flame iconography for Phynix Tech Services branding.
- **Meta & OpenGraph Headers**: Configured descriptive `<meta name="description">` tags, OpenGraph properties (`og:title`, `og:description`, `og:type`), and favicon declarations across all HTML documents (`index.html`, `web-services.html`, `qa-testing.html`, `infrastructure.html`, `contact.html`).
- **Semantic & Accessibility Enhancements**: Added `aria-current="page"` attributes to navigation links, associated form labels with form controls on the contact page using `for` and `id` attributes, and added `aria-required` properties for assistive technologies.

### Changed
- **UI & Design Overhaul**: Redesigned site visual presentation with a modern dark slate palette (`bg-slate-950`/`bg-slate-900`), custom gradient accents (`from-orange-500` to `from-amber-500`), refined typography, glassmorphism sticky header navigation, and interactive card hover transitions.
- **Global Navigation Consistency**: Standardized header and footer layouts across all 5 primary site pages (`index.html`, `web-services.html`, `qa-testing.html`, `infrastructure.html`, `contact.html`), providing uniform user experience across desktop and mobile screens.

### Fixed
- **Navigation & Broken Link Repairs**: Fixed missing links and routing inconsistencies on header/footer navigation across all pages (ensuring direct access to `contact.html` and service pages from any entry point).
- **Form Controls**: Added proper input element IDs (`full-name`, `email`, `practice-area`, `project-details`) matching corresponding `<label>` tags on `contact.html`.
- **Zero-JavaScript Mandate**: Verified strict adherence to zero custom client-side JavaScript across all pages while retaining responsive CSS layout functionality.
