# GitHub Profile README — Design Proposal

## Design System

### Color Palette (Dark Navy + Blue/Cyan Accents)
| Token | Hex | Usage |
|-------|-----|-------|
| `bg-deep` | `#07111f` | Page background, hero, cards |
| `bg-surface` | `#0b1a2f` | Card backgrounds, elevated surfaces |
| `bg-elevated` | `#112240` | Hover states, borders |
| `accent-cyan` | `#22d3ee` | Primary accent, links, highlights |
| `accent-blue` | `#38bdf8` | Secondary accent, gradients |
| `accent-deep` | `#0e7490` | Gradient fills, area charts |
| `text-primary` | `#f8fafc` | Primary text, headings |
| `text-secondary` | `#94a3b8` | Secondary text, descriptions |
| `text-muted` | `#64748b` | Labels, captions |
| `border-subtle` | `#1e3a5f` | Card borders, dividers |
| `border-focus` | `#22d3ee` | Focus rings, active states |

### Typography
- **Display/Headlines**: `Space Grotesk` (via Google Fonts) — geometric, technical, distinctive
- **Body/UI**: `IBM Plex Sans` — readable, engineering aesthetic
- **Code/Monospace**: `JetBrains Mono` — technical precision

### Layout Principles
- **Hero**: Full-width custom SVG banner with animated gradient mesh
- **Sections**: 1200px max-width, centered, generous vertical rhythm (64-96px between sections)
- **Cards**: Consistent 3-column grid (responsive to 2/1), equal heights, subtle hover elevation
- **Alignment**: Left-aligned content, centered section headers
- **Spacing**: 8px base unit, modular scale (8, 16, 24, 32, 48, 64, 96)

### Visual Identity Markers
1. **Custom hero banner** — SVG with animated mesh gradient, AngiSoft logo mark, tagline
2. **Technology grid** — Real logos from skillicons.dev / custom SVGs, grouped by domain
3. **Project cards** — Structured: thumbnail + title + tech pills + description + links
4. **GitHub stats** — Embedded activity graph (90 days), streak card, summary cards
5. **Section separators** — Thin gradient rules, not heavy HRs
6. **Consistent iconography** — Lucide icons for UI, brand logos for tech stack

---

## Proposed Section Structure

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  HERO BANNER (SVG)                                                          │
│  ─────────────────────────────────────────────────────────────────────────  │
│  [Animated gradient mesh]  AngiSoft Logo   "Silas Angera"                   │
│                         "Founder & Principal Engineer @ AngiSoft Technologies"│
│                         [CTA: View Work] [CTA: Contact]                     │
└─────────────────────────────────────────────────────────────────────────────┘
│  TECHNOLOGY EXPERTISE (icon grid, 4 columns × 4 rows)                       │
│  ┌─────────────┬─────────────┬─────────────┬─────────────┐                  │
│  │ Languages   │ Backend     │ Frontend    │ Data/DevOps │                  │
│  │ Java        │ Spring Boot │ React       │ PostgreSQL  │                  │
│  │ TypeScript  │ Node.js     │ Next.js     │ Redis       │                  │
│  │ Dart        │ Express     │ Flutter     │ Docker      │                  │
│  │ Python      │ Neon Auth   │ Tailwind    │ Kubernetes  │                  │
│  └─────────────┴─────────────┴─────────────┴─────────────┘                  │
└─────────────────────────────────────────────────────────────────────────────┘
│  FEATURED PROJECTS (3 cards, equal height)                                  │
│  ┌────────────────────┬────────────────────┬────────────────────┐           │
│  │ MboQara            │ PetroFlow Platform │ AngiSoft Platform  │           │
│  │ [screenshot]       │ [screenshot]       │ [architecture]     │           │
│  │ AI Career Platform │ ERP for Fuel       │ Multi-tenant       │           │
│  │ Flutter + Next.js  │ React + Spring     │ Spring Boot        │           │
│  │ [GitHub] [Live]    │ [GitHub] [Live]    │ [GitHub]           │           │
│  └────────────────────┴────────────────────┴────────────────────┘           │
│  ┌────────────────────┬────────────────────┬────────────────────┐           │
│  │ Basic Health Info  │ BMI Calculator     │ Company Portfolio  │           │
│  │ System             │                    │                    │           │
│  │ Flutter + Spring   │ Flutter            │ React + Express    │           │
│  │ [GitHub]           │ [GitHub] [Screens] │ [GitHub] [Live]    │           │
│  └────────────────────┴────────────────────┴────────────────────┘           │
└─────────────────────────────────────────────────────────────────────────────┘
│  GITHUB ECOSYSTEM (visual stats)                                            │
│  ┌──────────────────┬──────────────────┬──────────────────┐                  │
│  │ Activity Graph   │ Streak Stats     │ Top Languages    │                  │
│  │ (90 days)        │ (Current/Longest)│ (Dart/TS/Java/  │                  │
│  │                  │                  │  C++/HTML)       │                  │
│  └──────────────────┴──────────────────┴──────────────────┘                  │
│  Repos: 53  |  Stars: 29  |  Followers: 23  |  Orgs: AngiSoft Technologies   │
└─────────────────────────────────────────────────────────────────────────────┘
│  OPEN SOURCE & GISTS (selected)                                             │
│  • Java Tutorial Gists (17 gists — arrays, loops, regex, OOP)              │
│  • Dart/Flutter Examples (first-class functions)                           │
│  • VB.NET Basics (area, loops, types)                                      │
│  [View all gists →]                                                         │
└─────────────────────────────────────────────────────────────────────────────┘
│  PROFESSIONAL LINKS                                                         │
│  ┌──────────────┬──────────────┬──────────────┬──────────────┬────────────┐ │
│  │ Website      │ GitHub       │ LinkedIn     │ Twitter/X    │ Email      │ │
│  │ angisoft.co.ke│ Angera-Silas │ silas-angera │ angera_silas │ mailto     │ │
│  └──────────────┴──────────────┴──────────────┴──────────────┴────────────┘ │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## Assets to Create/Collect

| Asset | Source | Status |
|-------|--------|--------|
| Hero SVG banner | Custom (designed) | **Create** |
| AngiSoft full logo (dark) | `api.angisoft.co.ke/uploads/.../AngiSoft_Dark_Background_Logo-removebg.png` | ✅ Downloaded |
| AngiSoft symbol logo | `api.angisoft.co.ke/uploads/.../logo-symbol.svg` | ✅ Downloaded |
| MboQara logo/og-cover | `cdn.angisoft.co.ke/public/images/mboqara/og-cover.jpg` | ✅ Verified |
| PetroFlow logo | `api.angisoft.co.ke/uploads/.../petroflow-logo.png` | ✅ Downloaded |
| DukaFlow logo | `api.angisoft.co.ke/uploads/.../duka-flow-logo.png` | ✅ Downloaded |
| KejaLink logo | `api.angisoft.co.ke/uploads/.../keja-link-logo.png` | ✅ Downloaded |
| BMI Calculator screenshots | GitHub user-attachments (3 images) | ✅ Downloaded |
| GitHub activity graph | `github-readme-activity-graph` (Cloudflare Workers) | ✅ Working URL |
| Streak stats card | `streak-stats.demolab.com` | ✅ Working |
| Summary cards | `github-profile-summary-cards` | ✅ Working |

---

## Implementation Notes

1. **All images hosted on GitHub** — screenshots uploaded to this repo's `assets/` folder, referenced via `raw.githubusercontent.com`
2. **No external CSS/JS** — pure Markdown + HTML `<img>` + SVG, works on GitHub profile
3. **Responsive** — uses GitHub's native markdown rendering; images scale with `width="100%"`
4. **Accessible** — all images have `alt`, links have descriptive text, color contrast meets WCAG AA
5. **Performance** — images optimized (WebP where possible), lazy-loading via native `loading="lazy"`

---

## Approval Checkpoint

**Please confirm:**
1. ✅ Design direction (dark navy + cyan, Space Grotesk + IBM Plex Sans)
2. ✅ Section structure and project selection (6 projects as above)
3. ✅ Visual assets (logos, screenshots — all verified working)
4. ✅ GitHub stats cards (activity graph, streak, summary — all working)

Once approved, I'll implement the complete `README.md` and create the `assets/` folder with all images.