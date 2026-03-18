# Dane Lloyd MP Website — Context for site3 Build

This document provides full context for building **site3** (dane.sw7ft.com/site3) as a modern Tailwind website. Use it when starting a new thread.

---

## 1. Site Overview

**Domain:** dane.sw7ft.com  
**Subject:** Dane Lloyd, Member of Parliament for Parkland, Alberta  
**Riding stats:** 114,679 Canadians | 10,108 km² | 18 communities

---

## 2. Directory Structure

| Path | Purpose |
|------|---------|
| `/home/dane.sw7ft.com/public_html/` | **Original site** — Joomla-style static HTML, UIKit |
| `/home/dane.sw7ft.com/public_html/site2/` | **Partial Tailwind rebuild** — 3 of 5 pages done |
| `/home/dane.sw7ft.com/public_html/site3/` | **Target for new build** — full Tailwind site |

---

## 3. Source Files (Original Site)

All content and assets live under `public_html/`:

| File | Content |
|------|---------|
| `index.html` | Home — hero slideshow, Get Connected cards, district stats, community list, newsletter CTA, **floating chat widget** |
| `about-dane.html` | About Dane — full bio, photos |
| `contact-us.html` | Contact — form, office info, map |
| `community-news.html` | Community News — regional news cards (5 regions, 14 articles) |
| `stay-informed.html` | Get Connected — newsletter signup, social feeds |
| `stay-informed/get-involved.html` | Volunteer / careers |
| `stay-informed/contact-dane.html` | Redirects to contact |
| `stay-informed/social-media-feed.html` | Social media |
| `stay-informed/calendar.html` | Calendar |

---

## 4. Image Assets

All images are in `templates/yootheme/cache/` with hashed subdirs (e.g. `3d/`, `94/`). Paths are relative to `public_html/`.

### Logos
- **Dark logo (navbar):** `templates/yootheme/cache/3d/Asset-64x-3d3b7eda.png`
- **White logo (footer):** `templates/yootheme/cache/1a/Asset-64x-White-1acff90f.webp`

### Hero / Landscapes
- Wheat & mountains: `templates/yootheme/cache/94/photo-1558732599-2f570f74af6e-9419ddae.jpeg`
- Alberta fields: `templates/yootheme/cache/fe/field-of-rapeseeds-oilseed-rape-blutenmeer-yellow-46164-fee7bd52.jpeg`
- Landscape: `templates/yootheme/cache/84/Lucid_Realism_Wide_panoramic_landscape_of_rural_Alberta_featur_2-84af7102.jpeg`
- Small town: `templates/yootheme/cache/ed/Lucid_Realism_A_small_rural_Alberta_town_main_street_with_a_gr_2-ed4c2b70.jpeg`

### People / Community
- Stay Informed card: `templates/yootheme/cache/c2/photo-1588591644329-ea4fd16fc6f3-c2e5b228.jpeg`
- Contact card: `templates/yootheme/cache/33/photo-1586769852044-692d6e3703f0-336a48a3.jpeg`
- Volunteers: `templates/yootheme/cache/28/Lucid_Realism_cinematic_photo_closeup_of_Friendly_volunteers_g_0-280a8abd.jpeg`
- Albertans group: `templates/yootheme/cache/dd/Lucid_Realism_A_group_of_smiling_Albertans_with_diverse_facial_1-dd334a9a.jpeg`

### Dane Photos
- Professional: `templates/yootheme/cache/24/2025-0522-SVL-03-013-24e4dd91.jpeg`
- About page: `templates/yootheme/cache/10/Dane-About-2-1042d532.jpeg`
- Wedding/family: `templates/yootheme/cache/47/Dane-Lloyd-Wedding-47753706.jpeg`
- House of Commons: `templates/yootheme/cache/c1/Home-Header-Image-Dane-HOC-Scheer-Mobile-c10ece55.jpeg`

### Office
- Exterior: `templates/yootheme/cache/4d/Office Exterior-4d00a25c.jpeg` (note space in filename — use `%20` in URL)

### Icons
- Map marker: `images/yootheme/icon-xs-2-map-marker.svg`
- Favicon: `images/yootheme/icons/96x96-favicon.png`

### For site3
Use `../` prefix from `site3/` to reach parent `public_html/`:
- Logo: `../templates/yootheme/cache/3d/Asset-64x-3d3b7eda.png`
- Favicon: `../images/yootheme/icons/96x96-favicon.png`

---

## 5. Content Reference

### Bio (About Dane)
Dane grew up in and around the riding of Parkland. His family has farmed outside of Spruce Grove for generations, and he is a proud life-long Albertan. Dane, his wife Raechel and their three children Brooke, Alexander, and Harrison split their time between their home in Stony Plain and Ottawa.

Dane graduated from Edmonton Christian High School in 2009 and pursued a degree in history and political studies at Trinity Western University where he graduated with a Bachelor of Arts in 2014. Before serving as a member of Parliament, he worked as a Parliamentary Advisor to St. Albert-Edmonton MP Michael Cooper and the Honourable Ed Fast who served as the Minister of International Trade.

Dane is currently the Shadow Minister for Emergency Preparedness and Community Resilience. In July 2024, Albertans were devastated by the catastrophic wildfire in Jasper. As the Shadow Minister, Dane worked tirelessly to press the Liberal government for answers. The subsequent Parliamentary inquiry revealed that the Liberal government knew Jasper was in danger for years, but failed to act to remove dry, pine beetle-infested deadwood.

On top of his role in the Shadow Cabinet, Dane is a sitting member on the Standing Committee on Public Safety and National Security where he has fought hard against the Liberal gun confiscation regime. He was also at the forefront of the battle against foreign interference in our elections and improving Canada's cybersecurity legislation. Dane holds a commission as a Captain in the Canadian Armed Forces Primary Reserve.

### Office
- **Address:** #102-4807 44 Avenue, Stony Plain, AB T7X 1V5
- **Phone:** (780) 823-2050
- **Fax:** (780) 823-2055
- **Email:** dane.lloyd@parl.gc.ca

### Social Links
- Facebook: https://www.facebook.com/DaneLloydCPC
- X/Twitter: https://x.com/danelloydmp
- Instagram: https://www.instagram.com/danelloydcpc/
- YouTube: https://www.youtube.com/@danelloydmp4541
- Google Maps: https://maps.app.goo.gl/pxDHdQRrELZs5yEA8

### Community News (5 regions, 14 articles)
Full content in `community-news.html` — Spruce Grove & Stony Plain, Parkland County, Drayton Valley & Brazeau County, Mayerthorpe & Lac Ste. Anne County, Yellowhead County.

### 18 Communities
Cynthia, Brazeau County, Breton, Drayton Valley, Evansburg, Enoch, Entwistle, Kapasiwin, Lodgepole, Lac Ste. Anne County, Mayerthorpe, Parkland County, Seba Beach, Spruce Grove, Stony Plain, Tomahawk, Wildwood, Yellowhead County

---

## 6. Design System (from site2 plan)

- **Primary:** Navy `#003F72`
- **Dark navy:** `#0a2540`
- **Accent:** `#1e87f0`
- **Success:** `#A9F828`
- **Typography:** Inter (Google Fonts)
- **Stack:** Static HTML + Tailwind CDN + vanilla JS
- **Chat widget:** Demo mode, preset replies (Contact, About, Newsletter, Events)

---

## 7. What site2 Has (Reference)

| Page | Status | Notes |
|------|--------|-------|
| index.html | Done | Hero, stats, Get Connected cards, community mosaic, newsletter CTA, chat widget |
| about.html | Done | Bio, photos, highlight cards |
| contact.html | Done | Form, office info, map, office photo |
| community-news.html | **Missing** | Not built |
| stay-informed.html | **Missing** | Not built |

---

## 8. Pages to Build for site3

1. **index.html** — Home
2. **about.html** — About Dane
3. **contact.html** — Contact
4. **community-news.html** — Community News (card layout by region)
5. **stay-informed.html** — Stay Informed / Get Connected (newsletter, social links, Get Involved)

---

## 9. Shared Components

- Sticky navbar (logo, nav links, mobile hamburger)
- Footer (office, social, nav, copyright)
- Chat widget (home page only, demo mode)
- Newsletter CTA (inline form, demo submit)

---

## 10. Agent Work Summary (site2)

The agent:
1. Created `site2/` directory
2. Built `index.html` with Tailwind, hero, stats, Get Connected cards, community mosaic, newsletter CTA, chat widget
3. Built `about.html` with bio, photos, highlight cards
4. Built `contact.html` with form, office info, map, office photo
5. Did **not** complete `community-news.html` or `stay-informed.html`

---

## 11. Quick Start for site3

```
mkdir -p /home/dane.sw7ft.com/public_html/site3
```

Then build all 5 pages. Use `../templates/yootheme/cache/` and `../images/yootheme/` for assets. Copy nav/footer structure from site2. Add community-news and stay-informed pages.
