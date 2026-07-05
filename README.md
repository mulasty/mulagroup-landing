# Mula Group — Landing Page

Nowoczesny landing page premium dla Mula Group — zintegrowanego ekosystemu biznesowego łączącego AI, oprogramowanie, e-commerce, marketing, cyberbezpieczeństwo, budownictwo i startupy.

## Tech Stack

- **Next.js 16** (App Router)
- **TypeScript**
- **Tailwind CSS v4**
- **Framer Motion** (animacje)
- **Lucide React** (ikony)

## Struktura projektu

```
src/
├── app/
│   ├── globals.css          # Tailwind v4 + custom theme
│   ├── layout.tsx           # Root layout + SEO metadata + JSON-LD
│   ├── page.tsx             # Landing page (assembles all sections)
│   ├── robots.ts            # robots.txt
│   └── sitemap.ts           # sitemap.xml
├── components/
│   ├── Navbar.tsx           # Fixed glass-morphism navbar + mobile drawer
│   ├── HeroSection.tsx      # Full-viewport hero with glow animation
│   ├── AboutSection.tsx     # Company info + founder + values grid
│   ├── PillarsGrid.tsx      # 7 pillars grid container
│   ├── PillarCard.tsx       # Individual pillar card with hover glow
│   ├── ProcessSection.tsx   # 5-step model flow
│   ├── WhyUsSection.tsx     # Stats + value proposition
│   ├── TechnologyCloud.tsx  # Tech stack badges
│   ├── ProductsPreview.tsx  # Products in development
│   ├── ContactSection.tsx   # Contact info + CTA
│   ├── Footer.tsx           # Multi-column dark footer
│   ├── CTAButton.tsx        # Reusable animated CTA component
│   └── SectionHeader.tsx    # Reusable section heading
└── lib/
    ├── types.ts             # TypeScript interfaces
    ├── data.ts              # All content data (PL)
    └── utils.ts             # Helper utilities
```

## Sekcje strony głównej

1. **Hero** — tagline, CTA, animowane tło, statystyki
2. **O Mula Group** — opis firmy, założyciel, wartości
3. **7 filarów działalności** — AI, Transformacja Cyfrowa, E-commerce, Marketing, Cyberbezpieczeństwo, Budownictwo, Innowacje
4. **Jak pracujemy** — model 5-etapowy (Discover → Design → Integrate → Execute → Scale)
5. **Dlaczego Mula Group** — statystyki, przewagi
6. **Technologie** — chmura narzędzi
7. **Produkty w rozwoju** — produkty własne
8. **Kontakt** — dane kontaktowe + CTA

## Design

- **Dark premium** — grafitowe tło `#0a0a0a`
- **Electric blue** — akcent `#3b82f6`
- **Subtle purple** — `#8b5cf6`
- **Minimalistyczny, technologiczny, korporacyjny**
- **Mobile-first**, w pełni responsywny

## Development

```bash
npm install        # Instalacja zależności
npm run dev        # Start dev server (localhost:3000)
npm run build      # Build produkcyjny
npm run lint       # Linting
```

## Deployment (Vercel)

Projekt jest gotowy do wdrożenia na Vercel:

1. Push do repozytorium GitHub
2. Połącz z Vercel (automatycznie wykrywa Next.js)
3. Dodaj domenę `mulagroup.eu` w ustawieniach Vercel
4. Ustaw DNS A record `mulagroup.eu` → `76.76.21.21` (Vercel)
5. SSL certyfikat dodawany automatycznie przez Vercel

## Dane firmy

| Pole | Wartość |
|---|---|
| Nazwa | MULA GROUP SPÓŁKA Z O.O. |
| KRS | 0001010842 |
| NIP | 718-216-41-12 |
| Adres | ul. gen. Władysława Sikorskiego 166/0.03, 18-400 Łomża |
| Email | info@mulagroup.eu |
| Założenie | 2023 |
| Założyciel | Piotr Muła |

## Status

- [x] Next.js + TypeScript + Tailwind v4 setup
- [x] Wszystkie 13 komponentów UI
- [x] SEO metadata + schema.org + OG + sitemap
- [x] Animacje Framer Motion (stagger, fade-in, whileInView)
- [x] Responsive mobile-first
- [x] Build produkcyjny (zero błędów)
- [x] Treści PL (real copywriting, bez lorem ipsum)
- [ ] Deploy na Vercel
- [ ] Konfiguracja domeny mulagroup.eu
- [ ] Subdomeny dla 7 filarów

---

*Built with Matrix Multi-Agent System*
