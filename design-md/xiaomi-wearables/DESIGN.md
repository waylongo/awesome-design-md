# Design System Inspiration of Xiaomi Wearables

## 1. Visual Theme & Atmosphere

Xiaomi Wearables takes the broader Xiaomi retail system and compresses it into a health-focused, wrist-first visual language. The tone is energetic but controlled: black AMOLED watch faces, graphite dashboards, bright metric colors, rounded health cards, and the familiar Mi Orange (`#ff6900`) used as the brand anchor. Where the general Xiaomi system feels like a consumer electronics catalog, the wearables system feels like a daily activity cockpit: glanceable, biometric, personal, and always in motion.

The primary visual metaphor is the watch face. Circular and pill-shaped forms dominate: round activity rings, circular heart-rate modules, capsule sport chips, oval progress bars, and rounded device previews. Product cards should stage watches and smart bands as small high-contrast screens floating over neutral or graphite surfaces. UI details should feel optimized for quick checking: large numbers, compact labels, vivid status color, and clear icon/metric grouping.

Dark mode is not an afterthought. It should feel native to AMOLED displays and wearable dashboards: near-black backgrounds (`#050505`), graphite cards (`#151515`), subtle borders, and saturated but not neon data colors. Light mode remains useful for ecommerce and documentation, using Xiaomi's soft gray canvas and white cards, but the signature experience is dark surfaces with colored health telemetry.

Typography remains MiSans-first, with strong numerals and compact labels. Metrics are the hero typography: steps, BPM, sleep hours, calories, distance, battery, and VO2-style values should use large, confident numeric scales with tabular alignment. Text content should be short. Wearable UIs do not reward long paragraphs; they reward fast recognition.

**Key Characteristics:**
- AMOLED-first dark system with near-black backgrounds and graphite cards
- Mi Orange (`#ff6900`) as brand/action color, not the only data color
- Health data palette: heart red, activity green, sleep violet, GPS blue, energy amber
- Round activity rings, circular watch previews, and pill-shaped chips
- Big numeric metrics with compact uppercase labels
- Product surfaces for watches, bands, charging status, health cards, and sport modes
- Soft light retail mode for product catalog and comparison pages
- Motion-aware feel through progress rings, trend bars, and segmented activity states

## 2. Color Palette & Roles

### Primary Brand
- **Mi Orange** (`#ff6900`): Primary CTA, brand marker, selected state, active product highlight.
- **Orange Hover** (`#e95f00`): Hover and pressed state for primary actions.
- **Orange Glow** (`rgba(255,105,0,0.28)`): Focus rings, active watch-face glow, selected sport halo.
- **Soft Orange** (`#fff3eb`): Light-mode selected chip, sale badge background, promotional surface.

### AMOLED & Graphite
- **AMOLED Black** (`#050505`): Watch-face background, immersive dark dashboard canvas.
- **Graphite Page** (`#0d0d0d`): Dark page background and wearable app shell.
- **Graphite Card** (`#151515`): Dark health cards, metric modules, watch-face tiles.
- **Graphite Raised** (`#1f1f1f`): Elevated cards, modal panels, dark input surfaces.
- **Graphite Border** (`#2a2a2a`): Dark-mode dividers and card outlines.

### Light Surfaces
- **Page Gray** (`#f5f5f5`): Light retail page background.
- **Card White** (`#ffffff`): Product cards, spec panels, light dashboard cards.
- **Warm Surface** (`#fafafa`): Comparison sections and lower-emphasis tiles.
- **Light Border** (`#e6e6e6`): Dividers, product comparison borders, inactive chips.

### Health & Sport Data
- **Heart Red** (`#ff4d4f`): Heart rate, high-intensity zones, alerts.
- **Activity Green** (`#23c55e`): Steps, completed goals, recovery, positive status.
- **Sleep Violet** (`#8b5cf6`): Sleep, recovery, calm states, night mode.
- **GPS Blue** (`#1d9bf0`): Outdoor activity, maps, distance, connectivity.
- **Energy Amber** (`#f6b100`): Calories, energy, battery, warning states.
- **Oxygen Cyan** (`#22d3ee`): SpO2, breathing, water, freshness.

### Text
- **Text Primary Dark** (`#f5f5f5`): Main text on dark backgrounds.
- **Text Secondary Dark** (`#b8b8b8`): Secondary copy on dark backgrounds.
- **Text Muted Dark** (`#787878`): Small labels and inactive states on dark.
- **Text Primary Light** (`#191919`): Main text on light backgrounds.
- **Text Secondary Light** (`#595959`): Body copy and supporting descriptions.
- **Text Muted Light** (`#898989`): Metadata and helper labels.

### Gradients
- **Activity Ring Gradient**: `linear-gradient(135deg, #ff6900, #ff4d4f, #8b5cf6)`
- **Recovery Gradient**: `linear-gradient(135deg, #23c55e, #22d3ee)`
- **Outdoor Gradient**: `linear-gradient(135deg, #1d9bf0, #22d3ee)`
- **Sleep Gradient**: `linear-gradient(135deg, #312e81, #8b5cf6)`

## 3. Typography Rules

### Font Family
- **Primary**: `MiSans`, `MiSans Latin`, `Xiaomi Brand`, with fallback: `Arial`, `Helvetica Neue`, `Helvetica`, system sans-serif.
- **Numeric**: Same as primary with `font-variant-numeric: tabular-nums` for metrics, charts, timers, and battery values.
- **Monospace**: `SFMono-Regular`, `Roboto Mono`, `Menlo`, monospace for device model identifiers and firmware/spec strings.

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Watch Metric Hero | MiSans | 64px (4.00rem) | 700 | 0.95 | -0.6px | Steps, BPM, calories, sleep hours |
| Display Hero | MiSans | 52px (3.25rem) | 700 | 1.05 | -0.4px | Product launch hero headlines |
| Dashboard Heading | MiSans | 40px (2.50rem) | 700 | 1.10 | -0.2px | Wearable app and health dashboard headers |
| Product Tile Heading | MiSans | 30px (1.88rem) | 700 | 1.12 | normal | Watch/band product cards |
| Metric Value | MiSans | 28px (1.75rem) | 700 | 1.00 | normal | Card-level metric values |
| Card Heading | MiSans | 22px (1.38rem) | 600 | 1.20 | normal | Health modules and feature cards |
| Body Large | MiSans | 18px (1.13rem) | 400 | 1.45 | normal | Product subtitles and short intros |
| Body | MiSans | 16px (1.00rem) | 400 | 1.50 | normal | Standard copy |
| Metric Label | MiSans | 12px (0.75rem) | 700 | 1.00 | 0.4px | Uppercase card labels like BPM, STEPS, SLEEP |
| Button | MiSans | 14px (0.88rem) | 700 | 1.00 | normal | CTAs and sport chips |
| Caption | MiSans | 12px (0.75rem) | 400 | 1.35 | normal | Legal, helper, metadata |
| Micro Watch Label | MiSans | 10px (0.63rem) | 600 | 1.10 | 0.2px | Tiny watch-face labels |
| Spec Mono | Monospace | 13px (0.81rem) | 500 | 1.50 | normal | Device model, firmware, sensor strings |

### Principles
- **Numbers lead**: In health and fitness cards, numeric values should be visually dominant and labels should be short.
- **Tabular metrics**: Use tabular numerals for time, distance, BPM, battery, and progress values.
- **Short copy**: Avoid long explanatory text. Most modules should fit into a glanceable title, value, and one-line trend.
- **AMOLED contrast**: On dark cards, prioritize high contrast for numbers and data colors.
- **Rounded readability**: Use MiSans-like friendly forms, not condensed sports typography.

## 4. Component Stylings

### Buttons

**Primary Orange Pill**
- Background: `#ff6900`
- Text: `#ffffff`
- Padding: 12px 24px
- Radius: 999px
- Font: 14px MiSans weight 700
- Hover: `#e95f00`
- Focus: `0 0 0 4px rgba(255,105,0,0.28)`
- Use: Buy now, pair device, start workout, save watch face

**Graphite Pill**
- Background: `#151515`
- Text: `#f5f5f5`
- Border: `1px solid #2a2a2a`
- Padding: 12px 22px
- Radius: 999px
- Hover: `#1f1f1f`
- Use: Secondary dark-mode action

**Light Pill**
- Background: `#ffffff`
- Text: `#191919`
- Border: `1px solid #e6e6e6`
- Padding: 12px 22px
- Radius: 999px
- Hover: `#fafafa`
- Use: Secondary action on light product cards

### Watch Face Preview
- Shape: circular for watches, tall capsule for bands
- Background: `#050505`
- Border: 8px-12px solid device body color (`#1f1f1f`, silver, rose gold)
- Shadow: `0 30px 80px rgba(0,0,0,0.35)`
- Face content: large metric number, 2-4 small complication dots/cards, activity ring
- Use: hero visuals, product card imagery, watch-face galleries

### Activity Rings
- Size: 96px-180px depending on context
- Stroke width: 8px-14px
- Track: `rgba(255,255,255,0.10)` on dark, `#eeeeee` on light
- Progress: gradient or data-specific solid color
- Center content: large numeric value and short label
- Use: daily goal, calories, standing/activity progress, battery rings

### Health Metric Cards
- Dark background: `#151515`
- Light background: `#ffffff`
- Radius: 24px
- Padding: 20px-28px
- Border: `1px solid rgba(255,255,255,0.08)` on dark, none or `1px solid #eeeeee` on light
- Value: 28px-64px, weight 700, tabular numbers
- Label: uppercase 12px, muted color
- Trend row: small colored status dot, short text, sparkline or mini bars
- Use: heart rate, SpO2, sleep, stress, steps, calories, battery

### Sport Mode Chips
- Shape: 999px pill
- Height: 40px-44px
- Inactive dark: `#1f1f1f` background, `#b8b8b8` text, `1px solid #2a2a2a`
- Active dark: data-color background or `rgba(255,105,0,0.16)`, `#ff6900` text
- Inactive light: `#ffffff`, `#595959`, `1px solid #e6e6e6`
- Active light: `#fff3eb`, `#ff6900`
- Use: Running, Cycling, Swimming, Strength, Outdoor, Sleep

### Product Cards
- Background: light mode `#ffffff`; dark mode `#151515`
- Radius: 28px
- Padding: 28px
- Product preview: centered watch/band render with strong screen contrast
- Text: centered product name, one-line health/fitness promise, price/action row
- Hover: translateY(-2px), shadow increase
- Use: wearable catalog and comparison pages

### Charts & Trends
- Prefer compact visualizations: sparklines, seven-day bars, zone strips, ring progress
- Lines: 2px-3px rounded stroke
- Bars: 8px radius, 6px-10px width
- Label colors: muted, small, tabular
- Avoid dense financial-dashboard grids; wearable charts should be glanceable.

### Navigation
- Dark app nav: `rgba(5,5,5,0.86)` with blur and subtle border
- Light retail nav: `rgba(255,255,255,0.92)` with blur
- Links: 14px weight 600, muted by default, orange active state
- Mobile: horizontal chip navigation for product families and sport modes

## 5. Layout Principles

### Spacing System
- Base unit: 8px
- Scale: 4px, 8px, 12px, 16px, 20px, 24px, 32px, 40px, 48px, 64px, 80px
- Metric cards: 20px-28px padding
- Product cards: 28px-32px padding
- Dashboard gaps: 16px mobile, 20px tablet, 24px desktop
- Hero spacing: 64px desktop, 40px tablet, 28px mobile

### Grid & Container
- Dashboard max width: 1180px
- Product catalog max width: 1200px
- Health dashboard: 12-column desktop, 6-column tablet, 1-2 columns mobile
- Metric cards can vary in span: key metric cards span 2 columns, supporting cards span 1 column
- Watch-face gallery: circular previews in a responsive grid with equal aspect ratios

### Whitespace Philosophy
- **Glance first**: Give large metrics room. Do not bury data in paragraphs.
- **Wrist-scale logic**: Components should feel like enlarged wearable widgets, not generic web cards.
- **Color as data**: Use color to differentiate health categories, not as decoration.
- **Dark-first dashboards**: Health and watch-face views should be designed in dark mode first, then adapted to light.

### Shape Language
- Watch faces: circles and softened squares
- Smart bands: vertical capsules and long pills
- Metric cards: 20px-24px radius
- Product cards: 28px radius
- Chips/buttons: 999px pills
- Avoid sharp corners except for tiny chart bars where rounding would reduce clarity.

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| AMOLED Flat | `#050505`, no shadow | Watch face and dark page background |
| Graphite Surface | `#151515`, subtle border | Standard metric cards |
| Raised Card | `0 12px 32px rgba(0,0,0,0.28)` | Product cards and highlighted widgets |
| Watch Hardware | `0 30px 80px rgba(0,0,0,0.35)` | Device previews and hero watch renders |
| Overlay | `0 24px 64px rgba(0,0,0,0.48)` | Menus, watch-face picker, modals |
| Glow Focus | `0 0 0 4px rgba(255,105,0,0.28)` | Keyboard focus and active sport selection |

**Depth Philosophy**: Xiaomi Wearables depth is screen-like, not paper-like. Dark cards should separate through graphite contrast and thin borders. Product renders can carry stronger shadows because they represent physical devices. Data widgets should stay flat enough to feel like watch complications.

### Glow Rules
- Use subtle glow only around active rings, selected sport chips, or watch screens.
- Do not apply neon glows to all cards.
- Orange glow is for brand/action; data-color glow is reserved for the active metric.

## 7. Do's and Don'ts

### Do
- Design dark AMOLED dashboard states first
- Use large tabular metric numbers for BPM, steps, sleep, and battery
- Use circular rings and pill chips to echo watch and band shapes
- Keep Mi Orange for actions and selected states
- Assign semantic colors to health data categories
- Make watch/band previews high contrast and centered
- Keep labels short and uppercase for metric modules
- Use compact sparklines and bar trends rather than dense chart systems

### Don't
- Don't make everything orange; health categories need distinct colors
- Don't use long paragraphs inside metric cards
- Don't use generic phone ecommerce cards for watch dashboard views
- Don't make dark mode blue-black or neon gaming themed
- Don't overcomplicate watch faces with too many tiny labels
- Don't use hard square corners for wearable surfaces
- Don't hide trend/status context; metrics need direction and meaning
- Don't distort circular watch faces or pill-shaped band screens

## 8. Responsive Behavior

### Breakpoints
| Name | Width | Key Changes |
|------|-------|-------------|
| Mobile | <640px | Single-column dashboard, 2-column compact metric grid, horizontal chips |
| Tablet | 640-1024px | 2-column product grid, 6-column metric layout, reduced hero type |
| Desktop | 1024-1440px | 12-column dashboard, 3-column product cards, large watch preview |
| Large Desktop | >1440px | Centered content with expanded watch-face gallery spacing |

### Touch Targets
- Chips and buttons should be at least 44px tall
- Watch-face previews should be large tappable tiles, not tiny thumbnails
- Metric cards should be clickable as whole modules
- Ring controls need at least 48px center targets on mobile

### Collapsing Strategy
- Hero: watch preview stacks above text on mobile
- Dashboard: large metric cards become full-width, smaller metrics use 2-column grid
- Sport chips: wrap on desktop, horizontal scroll on mobile
- Charts: simplify labels and keep only primary trend lines on mobile
- Product cards: 3 columns -> 2 columns -> 1 column

### Watch Preview Behavior
- Keep circular watch faces circular at all breakpoints
- Use `aspect-ratio: 1 / 1` for watch previews
- Use `aspect-ratio: 0.45 / 1` or equivalent for band capsule previews
- Never crop the face or band screen so tightly that complications become unreadable

## 9. Agent Prompt Guide

### Quick Color Reference
- Primary CTA: Mi Orange (`#ff6900`)
- Dark Background: AMOLED Black (`#050505`)
- Dark Page: Graphite Page (`#0d0d0d`)
- Dark Card: Graphite Card (`#151515`)
- Light Background: Page Gray (`#f5f5f5`)
- Light Card: Card White (`#ffffff`)
- Heart Rate: Heart Red (`#ff4d4f`)
- Steps/Goal: Activity Green (`#23c55e`)
- Sleep: Sleep Violet (`#8b5cf6`)
- GPS/Distance: GPS Blue (`#1d9bf0`)
- Battery/Energy: Energy Amber (`#f6b100`)
- SpO2/Breathing: Oxygen Cyan (`#22d3ee`)

### Example Component Prompts
- "Create a Xiaomi Wearables dark health dashboard. Use #050505 page background and #151515 cards with 24px radius. The main metric card shows 8,642 steps in 64px MiSans weight 700 with tabular numbers, uppercase 12px label, and a circular activity ring using #ff6900 to #23c55e gradient."
- "Design a watch-face preview card: circular device body with #050505 screen, 10px graphite bezel, 0 30px 80px rgba(0,0,0,0.35) shadow. Inside the face, show a large BPM value, a red heart icon marker, small sleep and battery complications, and a colored progress ring."
- "Build a sport mode chip row for Xiaomi Wearables. Chips are 44px tall, 999px radius, inactive #1f1f1f with #b8b8b8 text and #2a2a2a border. Active Running chip uses rgba(255,105,0,0.16) background and #ff6900 text."
- "Create a light Xiaomi wearable product card. Use #ffffff background, 28px radius, 28px padding, centered watch render, title at 30px MiSans weight 700, subtitle 16px #595959, orange Buy now pill, and soft shadow."
- "Design a sleep insight card. Dark card #151515, 24px radius, violet accent #8b5cf6, 28px metric value '7h 42m', compact seven-day bar chart, and muted secondary text #b8b8b8."

### Iteration Guide
1. Start with dark AMOLED dashboard surfaces for health views.
2. Make numbers the strongest visual element in metric cards.
3. Use circular and pill geometry before generic rectangles.
4. Reserve Mi Orange for action, brand, and selected states.
5. Use semantic health colors consistently across cards and charts.
6. Keep labels short and uppercase.
7. Verify watch previews remain circular and band previews remain pill-shaped on mobile.
8. Avoid long body copy in dashboard modules; move details into supporting sections.
