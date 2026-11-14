# Awesome-Directory-Yellow-Pages-Listing

# Top Directory & Yellow Pages Listing Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Local Listings Management, Citation Building & Multi-Location SEO*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Directory & Yellow Pages Listing**. These tools help businesses manage their presence across online directories, search engines, and maps—covering citation accuracy, review monitoring, and multi-location data synchronization so customers find correct information everywhere.

**Examples** include Yext, BrightLocal, Birdeye, Moz Local, Uberall, Synup, Thryv, and open-source alternatives like TurnKey Directories and BusinessDirectory (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted business directories, open-source listing platforms, and community-driven local SEO tooling—ideal for organizations seeking data sovereignty and avoiding per-location SaaS fees. The open-source landscape is genuinely functional but narrow: **TurnKey Directories** provides a complete WordPress-based directory with maps and search [citation:1][citation:10], and **BusinessDirectory** offers a modern Next.js/Cloudflare Workers platform [citation:2]. Note that **open-source tools build directories you control**—they do not distribute listings to Google, Yelp, or other external networks like commercial platforms do.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Yext](https://www.yext.com/)** | Enterprise listings management with 200+ publisher integrations. Multi-product bundles (Listings, Pages, Reviews, Search, Analytics). Onboarding fees **$2,000–$20,000+** add 10–30% to first-year costs. Annual price escalators typically **3–7%** [citation:12]. | Small businesses (1–10 locations): **$2,500–$30,000/year**; single-product Listings only: ~**$1,000–$3,000/location/year** [citation:12] | No free tier; demo via sales |
| **[BrightLocal](https://www.brightlocal.com/)** | Local SEO platform with citation tracking, GBP audit, review monitoring, and Local Rank Tracker. Citation Builder is pay-as-you-go (**$2–$3.20/citation**). **14-day free trial**, no credit card [citation:4]. | From **$39/month** (Software Advice listing) [citation:13] | **14-day free trial** (full access, no card) [citation:4] |
| **[Birdeye](https://birdeye.com/)** | Reputation management and listings platform for multi-location businesses. Reviews across 200+ sites, listings management, AI insights. **Per-location pricing multiplies with no bundling** at lower tiers [citation:5][citation:14]. | Starter: **$299/location/month**; Growth: $349; Dominate: $449 [citation:5][citation:14] | No free tier; demo via sales. Contracts auto-renew with **1-year minimum** [citation:14] |
| **[Moz Local](https://moz.com/local)** | Local listings management and citation sync. Lite, Preferred, and Elite tiers. | Lite: **$16/month**; Preferred: $24; Elite: $33 (per user/month) [citation:6] | No free tier; trial available |
| **[Uberall](https://uberall.com/)** | Multi-location listings, reviews, and local social management. Essentials, Stand Out, and higher tiers. Add-ons for Reviews Plus, Analytics Plus, and Collaborate Plus [citation:7]. | Quote-only (tiered by locations/features) | No free tier; demo via sales |
| **[Synup](https://synup.com/)** | Agent-powered listings and local marketing platform. **All features included on every plan**—tiers change location capacity and agent task throughput, not feature access [citation:8]. | Solo: **$39/month** (1 location, annual); Premium: **$239/month** (10 locations, $23.90 effective per location) [citation:8] | No free tier; pricing calculator available |
| **[Thryv](https://www.thryv.com/)** | Small business platform consolidating CRM, scheduling, invoicing, and listings. Popular among construction, retail, and health businesses [citation:9]. | Quote-only (tiered by features) | Free trial available |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[TurnKey Directories](https://wordpress.org/plugins/turnkey-directories/)** | [![Stars](https://img.shields.io/github/stars/turnkeydirectories/turnkey-directories?style=social&color=white)](https://github.com/turnkeydirectories/turnkey-directories/stargazers) | **The most complete open-source WordPress business directory plugin.** Free plugin runs fully on its own—**no external services contacted unless you opt in**. Features: Leaflet/OpenStreetMap maps on directory pages, admin listing editor with Nominatim geocoding, Chart.js analytics, and jsVectorMap for geographic visualization [citation:1][citation:10]. **Pro add-on** (optional) adds bulk CSV/XLSX import, business-owner claims/portal, on-site reviews, multi-engine indexing (Google Indexing API + IndexNow), keyword-rank tracking, and Stripe subscription billing [citation:1]. **Best for WordPress sites needing a self-hosted directory with maps and search.** |
| **[BusinessDirectory](https://github.com/chamuditha4/BusinessDirectory)** | [![Stars](https://img.shields.io/github/stars/chamuditha4/BusinessDirectory?style=social&color=white)](https://github.com/chamuditha4/BusinessDirectory/stargazers) | **Modern open-source business directory built with Next.js, TypeScript, and Tailwind CSS.** Deployable to **Cloudflare Workers** for global performance. Uses PostgreSQL with automatic table creation for businesses, categories, service categories, and service options. **Data synced from a `data.json` file** via `pnpm run sync-postgresql`—supports bulk import and removal of stale listings. Required fields: title, place_id, GPS coordinates, address, city, country, category, type [citation:2]. **Best for developers wanting a modern, deployable directory without WordPress.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Adler Business Directory](https://wp-packages.org/packages/wp-plugin/adler-business-directory)** | — | Clean, simple WordPress business directory plugin for member, staff, church, HOA, and community listings. Search, categories, and photos included [citation:11]. **Best for simple community directories** without maps or advanced features. |

**Frameworks for building custom systems**: Choose **TurnKey Directories** for a WordPress-based directory with maps, search, and optional Pro add-ons for claims and reviews [citation:1]. Choose **BusinessDirectory** for a modern Next.js/Cloudflare Workers stack with PostgreSQL and JSON-driven data sync [citation:2]. **Neither distributes listings to external networks** (Google, Yelp, etc.)—if you need citation distribution across the web, commercial platforms (Yext, BrightLocal, Synup) are required.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Directory listing platforms handle business location data and potentially customer reviews; enforce accurate data entry, review moderation policies, and compliance with applicable consumer protection regulations.
- **Open-source tools build directories you own—they do not replace listing distribution.** TurnKey Directories and BusinessDirectory create searchable directories on your own domain [citation:1][citation:2]. They do **not** push data to Google Business Profile, Yelp, Apple Maps, or other publisher networks. **Commercial platforms charge for distribution and multi-location management**: Yext's onboarding fees alone add **$2,000–$20,000+** [citation:12]; Birdeye's per-location pricing multiplies at **$299–$449/month per location** with **1-year auto-renewing contracts** [citation:14]; Synup offers the most transparent entry at **$39/month for 1 location** [citation:8]. **Validate which external publishers you actually need** before committing to enterprise pricing—a self-hosted directory may suffice if your goal is a niche community listing rather than Google Maps visibility.

---

**Made for local marketers, multi-location businesses, and developers building directory infrastructure.**  
Let's make directory and yellow pages listing more open, accurate, and cost-predictable.
