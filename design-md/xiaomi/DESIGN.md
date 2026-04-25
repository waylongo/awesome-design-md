# Design System Inspiration of Xiaomi

## 1. Visual Theme & Atmosphere

Xiaomi's global website presents consumer technology as calm, accessible, and product-first. The dominant visual language is a soft retail gallery: pale gray page backgrounds (`#f5f5f5`), white product tiles (`#ffffff`), large centered device imagery, dark charcoal headings (`#191919`), and a single vivid brand accent, Mi Orange (`#ff6900`). It feels more approachable than luxury minimalism and more polished than a generic electronics store. The design goal is clear comparison, fast scanning, and broad-market confidence.

The system relies on high-radius geometry and balanced product staging. Cards usually read as rounded rectangles or soft squircles with 20px-28px radii, generous internal padding, and very light shadows. Product photography does most of the emotional work: phones, wearables, scooters, TVs, and smart-home products are placed on neutral surfaces with restrained text blocks. The interface avoids heavy borders, complex decoration, or aggressive gradients. When color appears, it is either the Xiaomi orange brand signal or a product-led accent pulled from device materials.

Typography is clean, rounded, and pragmatic. Xiaomi uses MiSans/MiSans Latin in brand environments; when unavailable, the closest behavior comes from `Arial`, `Helvetica Neue`, and system sans-serif fallbacks. Headlines use strong weights and tight but not severe line heights. Body copy remains neutral and compact, optimized for catalog cards, spec highlights, and price/action clusters. Letter-spacing stays near zero; the brand personality comes from geometry, spacing, and orange accents rather than from typographic tricks.

**Key Characteristics:**
- Mi Orange (`#ff6900`) as the unmistakable brand and action color
- Pale gray ecommerce canvas with white rounded product tiles
- MiSans-first typography with rounded, friendly sans-serif fallbacks
- Large centered product imagery with compact headline, price, and CTA groups
- Soft squircle geometry: 20px-28px for cards, 999px pills for CTAs/search
- Minimal shadows and borders; surfaces separate through background contrast
- Product-family navigation and dense comparison grids
- Dark theme uses graphite surfaces and orange accents without turning neon

## 2. Color Palette & Roles

### Primary
- **Mi Orange** (`#ff6900`): Primary brand color, CTA fills, active states, promotional labels, sale prices, and selected navigation.
- **Charcoal** (`#191919`): Primary headings, product names, strong labels, and dark buttons.
- **Pure White** (`#ffffff`): Card surfaces, navigation bars, modal panels, and text on dark/orange fills.

### Background & Surfaces
- **Page Gray** (`#f5f5f5`): Default page background. Soft enough to make product cards visible without heavy borders.
- **Warm Surface** (`#fafafa`): Alternate card and section surface, especially for product comparison areas.
- **Raised Surface** (`#ffffff`): Primary product tiles and navigation surfaces.
- **Soft Orange Surface** (`#fff3eb`): Promotional bands, active filter backgrounds, and orange-tinted badges.
- **Dark Graphite** (`#111111`): Dark-mode page background and premium product hero sections.
- **Graphite Card** (`#1f1f1f`): Dark-mode product tiles and panels.

### Text
- **Text Primary** (`#191919`): Main headings and product names.
- **Text Secondary** (`#595959`): Body copy, feature explanations, secondary nav text.
- **Text Muted** (`#898989`): Metadata, legal notes, inactive controls, helper text.
- **Text Disabled** (`#b0b0b0`): Disabled controls and unavailable product options.
- **Text Inverse** (`#ffffff`): Text over orange, black, or image-darkened hero areas.

### Interactive
- **Orange Hover** (`#e95f00`): Hover/pressed state for orange CTAs.
- **Orange Deep** (`#c84f00`): Active/pressed action state and strong price emphasis.
- **Black Button** (`#191919`): Secondary high-emphasis CTA on light product cards.
- **Black Hover** (`#3d3d3d`): Hover state for black CTAs.
- **Link Blue** (`#0b84ff`): Support, service, and account links where blue system semantics are expected.

### Borders & Dividers
- **Border Light** (`#e6e6e6`): Default dividers, card seams, nav separators.
- **Border Soft** (`#eeeeee`): Very light grid lines and product comparison borders.
- **Border Dark** (`#333333`): Dark-mode separators and card outlines.
- **Focus Ring** (`rgba(255,105,0,0.32)`): Keyboard focus and selected-control halo.

### Status & Product Accents
- **Success Green** (`#17a34a`): Availability, completed setup, positive status.
- **Warning Amber** (`#f5a623`): Promotions, stock warnings, shipping notices.
- **Error Red** (`#d93025`): Form errors, failed states.
- **Hyper Blue** (`#0b84ff`): OS, connectivity, and smart-device accents.
- **Product Silver** (`#d9dde3`): Device material backgrounds and neutral chips.

## 3. Typography Rules

### Font Family
- **Primary**: `MiSans`, `MiSans Latin`, `Xiaomi Brand`, with fallback: `Arial`, `Helvetica Neue`, `Helvetica`, system sans-serif.
- **Monospace**: `SFMono-Regular`, `Roboto Mono`, `Menlo`, monospace for specs, SKU strings, and technical labels.
- **Letter spacing**: Keep at `0` for almost all UI. Use only subtle negative tracking at very large display sizes.

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Display Hero | MiSans | 56px (3.50rem) | 700 | 1.05 | -0.4px | Large launch headlines and flagship hero copy |
| Hero Heading | MiSans | 48px (3.00rem) | 700 | 1.08 | -0.24px | Product family landing sections |
| Section Heading | MiSans | 36px (2.25rem) | 700 | 1.12 | normal | Catalog section headings |
| Product Tile Heading | MiSans | 28px (1.75rem) | 700 | 1.14 | normal | Main product names in tiles |
| Card Heading | MiSans | 22px (1.38rem) | 600 | 1.20 | normal | Feature card and comparison titles |
| Subheading | MiSans | 18px (1.13rem) | 600 | 1.35 | normal | Feature labels, tab headings |
| Body Large | MiSans | 18px (1.13rem) | 400 | 1.45 | normal | Intro copy and hero subtitles |
| Body | MiSans | 16px (1.00rem) | 400 | 1.50 | normal | Standard page text |
| Product Meta | MiSans | 14px (0.88rem) | 400 | 1.45 | normal | Price notes, availability, short specs |
| Button | MiSans | 14px (0.88rem) | 600 | 1.00 | normal | CTAs and compact controls |
| Navigation | MiSans | 14px (0.88rem) | 500 | 1.00 | normal | Header links and category tabs |
| Caption | MiSans | 12px (0.75rem) | 400 | 1.35 | normal | Legal text, helper labels, fine print |
| Badge | MiSans | 12px (0.75rem) | 600 | 1.00 | normal | New, sale, and status badges |
| Spec Mono | Monospace | 13px (0.81rem) | 500 | 1.50 | normal | Technical specs and model identifiers |

### Principles
- **Use MiSans-like roundness**: Prefer typefaces with friendly circular counters and open apertures. Avoid condensed or sharp editorial typefaces.
- **Strong but not loud**: Product names use weight 700, but body and metadata stay regular. Do not make the whole page bold.
- **Centered product tiles**: Product-card text is often centered and compact. Keep headings short and leave room for the image.
- **Normal tracking**: Xiaomi does not depend on extreme letter spacing. Keep text natural and highly readable.
- **Spec readability**: Use monospace only for technical values, SKU strings, and compact spec rows.

## 4. Component Stylings

### Buttons

**Primary Orange Pill**
- Background: `#ff6900`
- Text: `#ffffff`
- Padding: 12px 24px
- Radius: 999px
- Font: 14px MiSans weight 600
- Hover: `#e95f00`
- Focus: `0 0 0 4px rgba(255,105,0,0.32)`
- Use: Buy now, Learn more, promotional CTAs

**Black Pill**
- Background: `#191919`
- Text: `#ffffff`
- Padding: 12px 24px
- Radius: 999px
- Hover: `#3d3d3d`
- Use: Secondary hero CTA or high-emphasis action on light cards

**Ghost Orange**
- Background: transparent
- Text: `#ff6900`
- Padding: 10px 18px
- Radius: 999px
- Border: `1px solid rgba(255,105,0,0.35)`
- Hover: `#fff3eb` background
- Use: Secondary actions, comparison links, learn-more controls

**Plain Link**
- Text: `#ff6900`
- Font: 14px weight 600
- Hover: underline or slight color darkening to `#c84f00`
- Use: Product-card learn-more links where a pill would be too heavy

### Product Cards
- Background: `#ffffff`
- Radius: 24px standard, 28px for feature cards
- Border: none by default; use `1px solid #eeeeee` only when contrast is needed
- Shadow: `0 8px 24px rgba(0,0,0,0.04)`
- Hover: translateY(-2px), shadow intensifies to `0 16px 40px rgba(0,0,0,0.08)`
- Image: large centered product render, often 55%-70% of card height
- Text: centered title, short subtitle, price or CTA row
- Use: catalog grids, home feature tiles, device comparisons

### Hero Sections
- Background: `#f5f5f5`, `#ffffff`, or product/image-led neutral gradient
- Layout: product image dominates; text block centered or left-aligned depending on product composition
- Headline: 48px-56px, weight 700, `#191919`
- CTA group: orange pill plus black/ghost secondary action
- Use rounded section cards when hero appears inside a grid; use full-bleed product imagery for launch moments

### Navigation
- Sticky or fixed top bar, white or translucent white
- Height: 64px desktop, 56px mobile
- Background: `rgba(255,255,255,0.92)` with subtle blur
- Border-bottom: `1px solid #eeeeee`
- Links: 14px weight 500, `#595959`, hover `#191919`
- Active/selected: `#ff6900`
- Product category nav: horizontal scroll on mobile, pill or underline selected state

### Badges & Labels
**New Badge**
- Background: `#fff3eb`
- Text: `#ff6900`
- Padding: 5px 10px
- Radius: 999px
- Font: 12px weight 600

**Sale / Promo Badge**
- Background: `#ff6900`
- Text: `#ffffff`
- Padding: 5px 10px
- Radius: 999px
- Font: 12px weight 600

**Spec Chip**
- Background: `#f5f5f5`
- Text: `#595959`
- Border: `1px solid #eeeeee`
- Radius: 999px
- Padding: 8px 12px

### Inputs & Search
- Background: `#f5f5f5`
- Border: `1px solid transparent`
- Radius: 999px for search, 14px for forms
- Padding: 12px 16px
- Text: `#191919`
- Placeholder: `#898989`
- Focus: `1px solid #ff6900` plus `0 0 0 4px rgba(255,105,0,0.18)`

### Tabs & Filters
- Container: horizontal row with 8px gap
- Default chip: `#ffffff` background, `#595959` text, `1px solid #e6e6e6`
- Active chip: `#191919` background, `#ffffff` text, or `#fff3eb` background with `#ff6900` text for brand-heavy pages
- Radius: 999px
- Mobile: horizontal scroll with snap points

## 5. Layout Principles

### Spacing System
- Base unit: 8px
- Scale: 4px, 8px, 12px, 16px, 20px, 24px, 32px, 40px, 48px, 64px, 80px, 96px
- Product cards: 24px-32px padding
- Section padding: 64px desktop, 40px tablet, 28px mobile
- Card gaps: 16px mobile, 24px desktop

### Grid & Container
- Max content width: 1200px for catalog pages, 1440px for image-heavy home pages
- Standard grid: 12 columns desktop, 6 columns tablet, 1-2 columns mobile
- Product cards: 2-4 columns desktop depending on product density
- Hero: full-width band or large rounded tile, never cramped
- Comparison/spec tables: centered max-width with soft dividers

### Whitespace Philosophy
- **Retail clarity**: Leave enough air around each product image for easy scanning and comparison.
- **Soft separation**: Prefer background contrast and rounded cards over heavy outlines.
- **Information hierarchy**: Product name first, short value proposition second, price/status third, CTA last.
- **Dense where practical**: Category tabs, spec chips, and comparison rows can be compact as long as product cards stay spacious.

### Shape Language
- Cards: 20px-28px rounded rectangles
- Buttons and chips: 999px pills
- Inputs: 14px or 999px depending on density
- Image masks: 20px-24px radius if product imagery needs containment
- Avoid sharp corners on major surfaces; Xiaomi's retail system is friendly and rounded.

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Flat | No shadow, `#f5f5f5` background | Page background and section bands |
| Surface | White card, no shadow | Dense catalog cards and comparison rows |
| Raised | `0 8px 24px rgba(0,0,0,0.04)` | Standard product cards |
| Hover | `0 16px 40px rgba(0,0,0,0.08)`, translateY(-2px) | Interactive product cards |
| Overlay | `0 24px 64px rgba(0,0,0,0.14)` | Menus, modals, quick-view panels |
| Focus | `0 0 0 4px rgba(255,105,0,0.32)` | Keyboard focus and selected controls |

**Depth Philosophy**: Xiaomi uses low-contrast depth. Surfaces should feel touchable and friendly, not glassy or dramatic. Shadows stay broad, soft, and low-opacity. Most separation comes from the page-gray background against white product cards. Dark sections reverse this relationship with graphite cards on a near-black canvas.

### Image Depth
- Product images may cast natural photographic shadows, but UI shadows should remain subtle.
- Avoid heavy drop shadows under text or icons.
- On dark backgrounds, use slightly brighter card surfaces (`#1f1f1f`) instead of strong glow effects.

## 7. Do's and Don'ts

### Do
- Use Mi Orange (`#ff6900`) for primary actions, active states, and brand moments
- Place product imagery at the center of cards and let it occupy significant space
- Use pale gray page backgrounds with white rounded product tiles
- Keep border radii generous on cards and pills
- Use compact, centered text stacks for product cards
- Use normal letter spacing and friendly sans-serif typography
- Keep shadows soft and low-opacity
- Support dense product grids without making individual cards feel cramped

### Don't
- Don't overuse orange across large backgrounds; reserve it for focus and action
- Don't use sharp-cornered enterprise panels for consumer product pages
- Don't apply heavy borders around every card
- Don't use saturated gradients unless a product campaign specifically needs them
- Don't use decorative patterns that compete with product photography
- Don't make typography overly editorial, condensed, or high-contrast serif
- Don't use neon dark-mode accents; Xiaomi dark mode remains graphite and restrained
- Don't bury price, availability, or CTA information below long paragraphs

## 8. Responsive Behavior

### Breakpoints
| Name | Width | Key Changes |
|------|-------|-------------|
| Mobile | <640px | Single-column hero, 1-2 product columns, horizontal category scroll |
| Tablet | 640-1024px | 2-column product grids, reduced hero type, moderate padding |
| Desktop | 1024-1440px | 3-4 column grids, full navigation, large hero product imagery |
| Large Desktop | >1440px | Centered 1440px canvas with spacious product staging |

### Touch Targets
- Buttons and chips should be at least 44px tall
- Product cards should have large clickable regions, not tiny text-only links
- Category tabs use horizontal scroll on mobile with clear active state
- Search inputs use 48px height on mobile

### Collapsing Strategy
- Hero: image stacks above or below text depending on product composition
- Product grids: 4 columns -> 2 columns -> 1 column for large cards
- Category navigation: full menu -> horizontal scroll chips -> compact menu
- Comparison tables: cards or horizontally scrollable rows on mobile
- CTA groups: inline pills -> stacked or wrapped pills
- Section spacing: 64px desktop -> 40px tablet -> 28px mobile

### Image Behavior
- Product renders remain centered and uncropped whenever possible
- Use `object-fit: contain` for catalog cards
- Preserve aspect ratios for device imagery to avoid distorted phones, TVs, and wearables
- Reduce image height on mobile but keep enough space for recognition

## 9. Agent Prompt Guide

### Quick Color Reference
- Primary CTA: Mi Orange (`#ff6900`)
- CTA Hover: Orange Hover (`#e95f00`)
- Background: Page Gray (`#f5f5f5`)
- Card Surface: Pure White (`#ffffff`)
- Heading Text: Charcoal (`#191919`)
- Body Text: Text Secondary (`#595959`)
- Muted Text: Text Muted (`#898989`)
- Border: Border Soft (`#eeeeee`)
- Dark Background: Dark Graphite (`#111111`)
- Dark Card: Graphite Card (`#1f1f1f`)
- Focus Ring: `rgba(255,105,0,0.32)`

### Example Component Prompts
- "Create a Xiaomi-style product card on a #f5f5f5 page. Card background #ffffff, 24px radius, 32px padding, subtle shadow 0 8px 24px rgba(0,0,0,0.04). Center a large product image using object-fit: contain. Title 28px MiSans weight 700 color #191919, subtitle 16px #595959, price in #ff6900. Add an orange pill CTA with 999px radius."
- "Build a Xiaomi hero section with a pale gray background, 56px MiSans weight 700 headline in #191919, 18px body copy in #595959, and two pill buttons: primary #ff6900 with white text and secondary #191919 with white text. Keep the product render large, centered, and uncropped."
- "Design a Xiaomi category filter row. Use 999px chips, 44px minimum height, white background and #e6e6e6 border for inactive chips. Active chip uses #fff3eb background and #ff6900 text. On mobile, make the row horizontally scrollable."
- "Create a dark Xiaomi product showcase. Background #111111, cards #1f1f1f, text #ffffff and #c7c7c7, orange CTAs #ff6900. Keep shadows minimal and rely on graphite surface contrast."
- "Make a Xiaomi search field: #f5f5f5 background, 999px radius, 12px 16px padding, placeholder #898989, focus border #ff6900 and 4px orange translucent focus ring."

### Iteration Guide
1. Start with page gray background and white rounded product tiles.
2. Use Mi Orange only where action or brand emphasis is needed.
3. Product imagery should be the largest visual element in most components.
4. Use generous radii: 24px cards, 999px buttons/chips/search.
5. Keep typography clean, rounded, and normally tracked.
6. Avoid heavy shadows; separate with surface contrast first.
7. Check mobile card layouts early so product images do not crowd titles.
8. Dark mode should feel like graphite retail UI, not a neon gaming theme.
