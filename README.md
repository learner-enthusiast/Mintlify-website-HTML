# Mintlify Landing Page Clone

A pixel-perfect recreation of the Mintlify documentation platform landing page.

## Screenshot

![Mintlify Clone Screenshot](assets/mintlify-html.netlify.app_.png)

---

## Sections Recreated

### 1. Header
- Fixed navigation bar with glassmorphism effect
- Logo, navigation links, and CTA buttons
- Blur backdrop filter for modern look

### 2. Hero Section (Container 1)
- Full-screen hero with background image
- "NEW" badge with announcement text
- Main headline and subtitle
- Email input with "Start now" CTA button
- Hero product image

### 3. Logo Grid (Container 2)
- 4x2 grid of partner/customer logos
- Includes: Anthropic, Coinbase, Microsoft, Perplexity, HubSpot, X, PayPal, Lovable

### 4. Features Section (Container 3)
- "Built for the Intelligence Age" header
- Two feature cards (LLMS.TXT & MCP, Agent)
- Assistant section with full-width card

### 5. Enterprise Section (Container 4)
- Enterprise header with CTA button
- Two enterprise feature highlights
- Customer story card (Anthropic) with stats
- Enterprise logos row

### 6. Customers Carousel (Container 5)
- Pure CSS carousel (no JavaScript)
- Customer story cards: Perplexity, X, Kalshi, Cognition, Together AI, Laravel, Replit
- Navigation arrows with radio button controls

### 7. CTA Section (Container 6)
- Main call-to-action with headline
- Primary and secondary buttons
- Two feature cards (Pricing, Quickstart)

### 8. Footer
- Logo and social links (LinkedIn, X/Twitter, GitHub)
- 5-column link grid (Explore, Resources, Documentation, Company, Legal)
- Security badge (SOC II)
- Status indicator, copyright, and theme toggles

---

## Fonts

| Font | Usage |
|------|-------|
| **Inter** | Primary font for all text |

```css
font-family: 'Inter', sans-serif;
```

---

## Colors

### Background Colors

| Color | Value | Usage |
|-------|-------|-------|
| Dark Background | `lab(2.42579 -0.165291 -0.470081)` / `#0f1117` | Main page background |
| Card Background | `#0a0c10` | Feature cards, sections |

### Text Colors

| Color | Value | Usage |
|-------|-------|-------|
| White | `lab(100 0 0)` / `#fff` | Primary text |
| White 70% | `lab(100 0 0 / 0.7)` / `rgba(255, 255, 255, 0.7)` | Subtitles, descriptions |
| White 60% | `rgba(255, 255, 255, 0.6)` | Secondary text |
| White 50% | `rgba(255, 255, 255, 0.5)` | Muted text, labels |
| White 40% | `rgba(255, 255, 255, 0.4)` | Footer titles |

### Accent Colors

| Color | Value | Usage |
|-------|-------|-------|
| Green (Primary) | `#22c55e` | Labels, icons, status dot |
| Green (Lab) | `lab(79.9844 -59.6292 22.5096)` | Feature labels |
| Green (Badge) | `lab(51.3415 -41.5657 15.3527)` | "NEW" badge |
| Hover Green | `#18E299` | Link hover states |

### Button Colors

| Color | Value | Usage |
|-------|-------|-------|
| White | `#fff` | Primary buttons |
| White Hover | `#e5e5e5` | Primary button hover |
| Dark Text | `#0f1117` | Button text on white |

### Border & Glass Effects

| Color | Value | Usage |
|-------|-------|-------|
| Border Light | `rgba(255, 255, 255, 0.1)` | Card borders, dividers |
| Border Medium | `rgba(255, 255, 255, 0.2)` | Buttons, inputs |
| Border Strong | `rgba(255, 255, 255, 0.3)` | Secondary buttons |
| Glass Background | `rgba(255, 255, 255, 0.08)` | Glassmorphism effect |

---

## CSS Features Used

- **CSS Grid** - Logo grids, feature layouts, footer columns
- **Flexbox** - Navigation, cards, alignments
- **Glassmorphism** - Header and input effects using `backdrop-filter`
- **CSS Lab Colors** - Modern color space for precise colors
- **Pure CSS Carousel** - Radio button controlled slider
- **CSS Transitions** - Hover effects and animations
- **Responsive Design** - Media queries for mobile support

---

## File Structure

```
mintlify/
├── index.html          # Main HTML file
├── styles.css          # All styles
├── README.md           # This file
└── assets/             # Images and icons
    ├── mintlifyIcon.svg
    ├── bg-dark.svg
    ├── hero-image.png
    ├── right-arrow.svg
    ├── ss.png
    └── ... (logo files)
```

---

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

> Note: `lab()` color functions require modern browser support. Fallback hex colors are provided where critical.