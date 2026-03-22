# CLAUDE.md — Casa Arouquesa Website Build

## Purpose

This project has a single objective: **build the Casa Arouquesa restaurant website** (casaarouquesa.pt). All work in this folder is focused exclusively on creating a modern, premium website for this restaurant. Nothing else.

## Scope

- **What we are doing:** Building the Casa Arouquesa website from scratch using the content, structure, and assets extracted from the original site.
- **What we are NOT doing:** Anything unrelated to this website. This folder is dedicated solely to this build.

## Source Material

All original site content, structure, and assets are documented in these reference files — **always consult them before building any page or component:**

| File | Purpose |
|------|---------|
| [SITE-INDEX.md](casaarouquesa-rip/SITE-INDEX.md) | Full site map, contact info, business hours, asset inventory, content file index |
| [casaarouquesa-rip/content/pages/](casaarouquesa-rip/content/pages/) | Page content (home, apresentacao, conceito, ementa, galeria, eventos, media, contactos, reservas) |
| [casaarouquesa-rip/content/metadata/](casaarouquesa-rip/content/metadata/) | Contact details, policies, external links |
| [casaarouquesa-rip/assets/](casaarouquesa-rip/assets/) | All downloaded assets (90 files across branding, hero, food, events, gallery) |

## Restaurant Identity

- **Name:** Casa Arouquesa
- **Type:** Premium restaurant specializing in Arouquesa beef (carne Arouquesa)
- **Location:** Empreendimento Bellavista, Lote 0, Repeses 3500-680 Viseu, Portugal
- **Phone:** +351 232 416 174
- **Email:** geral@casaarouquesa.pt
- **Languages:** Portuguese (primary), English, Spanish
- **Hours:** Mon-Fri 12:15-15:00 / 19:15-22:00 | Sat 12:15-15:00 / 19:15-22:30 | Sun closed
- **Signature dishes:** Vitela Assada no Forno (roasted veal), Bife Arouques a Casa (Arouquesa steak)
- **Character:** Refined, modern atmosphere with exceptional wine cellar. Focused on healthy cuisine showcasing the quality and individual value of each product. Tells stories through flavors and aromas.

## Asset Organization

```
casaarouquesa-rip/
├── SITE-INDEX.md              <- Master reference for everything
├── assets/
│   ├── branding/              <- Logo, footer logos, EU funding badges, Restaurant Guru badge
│   ├── hero/                  <- 4 homepage hero/slider images
│   ├── icons/                 <- Language flags (pt, en, es)
│   ├── food/                  <- 6 food/dish photographs
│   ├── events/                <- 7 event images (Valentine's, Women's Day, COVID, Joao Felix)
│   └── gallery/
│       ├── remodelacao-2019/  <- 16 renovation interior shots
│       ├── nova-imagem/       <- 6 professional restaurant photos
│       ├── jantar-ruinart/    <- 7 Ruinart champagne dinner photos
│       ├── jantar-quinta-carolina/ <- 7 wine dinner photos
│       ├── jantar-vinhapaz/   <- 7 wine dinner photos
│       └── personalidades/    <- 20 celebrity/personality visit photos
└── content/
    ├── pages/                 <- 9 page content files (PT text)
    └── metadata/              <- Contact, policies, external links
```

## Site Pages to Build

| Page | Content Source | Key Elements |
|------|---------------|-------------|
| Home | home.md | Hero slider (4 images), specialties preview, wine cellar mention, gallery teaser |
| Apresentacao | apresentacao.md | Restaurant presentation, history, hours, location |
| Conceito | conceito.md | Cuisine philosophy — healthy, product-focused, Arouquesa beef |
| Ementa | ementa.md | Full menu: specialties, starters, mains, sides, desserts |
| Galeria | galeria.md | 6 photo albums with detail views |
| Eventos | eventos.md | Past events (Valentine's dinners, Women's Day, wine dinners) |
| Media | media.md | News articles (renovation, COVID measures, Joao Felix visit) |
| Contactos | contactos.md | Contact form, address, map, hours |
| Reservas | reservas.md | Online reservation form (up to 30 guests) |

## Design Skill

This project uses the **taste-skill** for frontend design guidance. The skill file is at [taste-skill.md](taste-skill.md) and the reference doc is at [SKILL-REFERENCE.md](SKILL-REFERENCE.md).

**Always apply taste-skill directives when building frontend components.** Key parameters:

| Parameter | Value | Meaning |
|-----------|-------|---------|
| DESIGN_VARIANCE | 8 | Asymmetric layouts, masonry grids, large empty zones |
| MOTION_INTENSITY | 6 | Fluid CSS transitions, animation-delay cascades, spring physics |
| VISUAL_DENSITY | 4 | Daily app mode — normal spacing, clean and breathable |

### Design Considerations for This Restaurant

- **Tone:** Refined, warm, premium but not pretentious. This is a beloved neighborhood institution with celebrity visitors and an excellent wine cellar — not a Michelin-starred temple. The design should feel inviting and sophisticated.
- **Palette direction:** Warm neutrals (slate/zinc base) with a singular rich accent — consider deep burgundy/wine, warm amber, or earthy emerald to echo the meat-and-wine identity. No purple, no neon.
- **Typography:** Premium sans-serif (Geist, Satoshi, or Cabinet Grotesk). Consider a refined serif only for editorial/decorative elements like menu headings.
- **Photography is the hero:** This site has excellent food and interior photography. Let images breathe. Large, full-bleed where appropriate.
- **Multilingual:** Support PT (primary), EN, and ES. The original site had language flag toggles.

## Instructions for Claude

1. **Stay focused.** Every task in this folder relates to building the Casa Arouquesa website.
2. **Reference SITE-INDEX.md and content files** before building any page — do not invent content.
3. **Use existing assets** from `casaarouquesa-rip/assets/`. Do not create placeholder images when real photos are available.
4. **Apply the taste-skill** on every frontend component. Follow its rules on typography, color, layout, motion, forbidden patterns, and the pre-flight checklist.
5. **Support PT, EN, and ES.** Portuguese is the primary language.
6. **Keep external links intact** — Facebook, Restaurant Guru, complaints book, EU funding partner links.
7. **Respect the restaurant's identity** — two signature dishes, exceptional wine cellar, modern-yet-traditional character, Viseu location.
