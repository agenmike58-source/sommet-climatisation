# Sommet Climatisation — Website Build Spec

## Business
- **Name:** Sommet Climatisation
- **Trade:** HVAC (chauffage, climatisation, thermopompes, ventilation)
- **Location:** Montréal, Quebec, Canada
- **Language:** French (100%)
- **Tagline:** "Votre confort, notre sommet"

## Tech Stack
- Static HTML + Tailwind CSS (CDN)
- Zero frameworks, zero build tools
- Single index.html + assets folder
- Must load under 1 second

## Design Direction
- Modern, clean, lots of whitespace
- Dark navy (#1a2744) + ice blue (#4da8da) + white palette — mountain/summit theme
- Mobile-first responsive
- Sticky header with phone + CTA
- Smooth scroll, subtle animations (CSS only, no JS libraries)
- Beat Quebec competitors (klimfax.com, excelclimatisation.com, confortexpert.com) — they have content but ugly WordPress designs

## Pages (all in one index.html, section-based)
1. **Hero** — full-width gradient/image bg, business name, tagline, phone number, "Soumission gratuite" CTA button
2. **Stats bar** — 4 stats: "15+ années d'expérience", "2000+ projets", "4.9/5 avis Google", "Service 24/7"
3. **Services** — grid of 6 cards with icons: Thermopompes, Climatisation, Chauffage, Ventilation, Entretien préventif, Service d'urgence
4. **Pourquoi nous choisir** — 4 feature blocks: Techniciens certifiés, Soumission gratuite, Garantie satisfaction, Prix compétitifs
5. **Subventions** — section about Hydro-Québec and Énergir rebates (big selling point in Quebec)
6. **Réalisations** — placeholder gallery grid (before/after style)
7. **Témoignages** — 3 customer review cards with names and cities
8. **Zones desservies** — list of areas: Montréal, Laval, Longueuil, Rive-Nord, Rive-Sud, Ouest-de-l'Île
9. **Contact/Soumission** — form (nom, téléphone, courriel, type de service dropdown, message) + phone + email + address placeholder
10. **Footer** — logo text, nav links, phone, email, social icons placeholders, RBQ# placeholder, copyright

## Must Have
- Schema.org LocalBusiness + Service markup (JSON-LD in head)
- Open Graph meta tags
- Proper SEO title: "Sommet Climatisation | Chauffage et Climatisation à Montréal"
- Meta description in French
- Favicon placeholder
- Google Fonts: Inter or similar clean sans-serif
- All placeholder images use solid color blocks or CSS gradients (no external image URLs)
- Accessible: proper heading hierarchy, alt texts, aria labels on buttons
- Print-friendly basics

## Do NOT include
- No JavaScript frameworks
- No external image dependencies
- No Lorem ipsum — all text must be real French HVAC content
- No English anywhere
