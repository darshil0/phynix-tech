# Changelog

All notable changes to the Phynix Tech Services website project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2026-03-30

### Added
- **Light / Dark Mode Support**: Integrated theme toggles in primary page headers and mobile navigation bars across all pages (`index.html`, `web-services.html`, `qa-testing.html`, `infrastructure.html`, `contact.html`).
- **FOUT Prevention Theme Script**: Implemented lightweight, inline head JavaScript checking `localStorage` preference and `prefers-color-scheme` media query to apply dark mode classes immediately prior to render.
- **Corporate Contact Block**: Created minimal, clean corporate contact section on `contact.html` featuring Dallas Headquarters office address (111 W Mockingbird Ln, Dallas, TX 75247, USA), direct mailto email link (`contact@phynixtech.com`), and CST operating hours / support availability.

### Changed
- **Minimalist UI Redesign**: Overhauled site-wide layout aesthetics with increased whitespace padding, clean slate typography hierarchy (`text-slate-600` / `dark:text-slate-400`), subtle thin borders (`border-slate-200` / `dark:border-slate-800`), and flat clean buttons/badges.
- **Documentation Update**: Updated `README.md` to reflect the multi-page static architecture with Light/Dark mode support, static corporate contact block details, directory structure, and local preview instructions.

### Removed
- **Inquiry Form & Section Removal**: Audited and completely removed the "Direct Inquiry" form element and form controls from `contact.html` and all other sub-pages in favor of direct corporate contact details.

### Fixed
- **Navigation & Routing Alignment**: Verified and fixed all anchor link routes, navigation active state highlighting (`aria-current="page"`), meta tags (`viewport`, `charset`, page titles, OpenGraph), decorative icons (`aria-hidden="true"`), and `.nojekyll` GitHub Pages bypass support.
