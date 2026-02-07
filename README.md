# Vidor OS Website

Professional, responsive website for Vidor OS - a lightweight, CLI-first Linux distribution based on Debian Bookworm.

## Project Overview

This website serves as the official distribution platform for Vidor OS, featuring:
- Modern, responsive design supporting all device sizes (mobile, tablet, desktop, TV)
- Black and red (#DC143C) color scheme
- Version archive system with date-based downloads
- Comprehensive documentation and community resources
- Custom shark cursor for enhanced UX

## Features

### Responsive Design
- Mobile (480px-): Optimized for phones
- Tablet (768px): Enhanced layout for tablets
- Desktop (1024px+): Full desktop experience
- TV (1920px+): Large screen support with clamp fluid typography

### Version Archive System
Users can select any date (Feb 7, 2026 - Dec 31, 2026) to download specific ISO versions:
- Automatic file detection
- Date-based folder structure: DD-MM-YYYY
- File naming: vidoros-DD-MM-YYYY.iso
- SHA256 checksum downloads for verification

### Technical Documentation
- Debian Bookworm base system
- Legacy BIOS boot support
- Custom WiFi drivers (Realtek RTL8812AU, Atheros)
- ThinkPad device optimization

## Adding ISO Files

To add a new version to the archive, create a folder named with the current date (DD-MM-YYYY) inside the downloads directory and place the ISO file along with its SHA256 checksum. 

Note: ISO files should be managed via LFS or external hosting due to GitHub file size limits.

## Page Navigation

| Page | File | Purpose |
|------|------|---------|
| Home | index.html | Main landing page with news and gallery |
| Packages | pages/packages.html | Package repository information |
| Community | pages/community.html | Community guidelines and channels |
| Documentation | pages/documentation.html | Technical docs and system info |
| Issues | pages/issues.html | Issue tracking and bug reports |
| Download | pages/download.html | ISO downloads and version archive |

## Vidor OS Technical Specifications

- Base System: Debian Bookworm
- Boot: Legacy BIOS
- Philosophy: CLI-first, English-based, power user focused
- Optimization: Built for ThinkPad laptops and penetration testing

## Deployment

This website is static HTML/CSS/JS and can be deployed to GitHub Pages, Netlify, Vercel, or any traditional local web server.

## Contributing

1. Bug Reports: Use the Issues page to report system bugs.
2. Web Improvements: Submit Pull Requests for UI/UX enhancements.
3. Documentation: Help improve technical docs in the pages directory.

---
Vidor OS is a community-driven project.

