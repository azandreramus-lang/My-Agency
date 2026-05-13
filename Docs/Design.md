{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 ## Overview\
\
Claude.com is the warmest, most editorial interface in the AI-product category. The base atmosphere is a **tinted cream canvas** (`\{colors.canvas\}` \'97 #faf9f5) \'97 distinctly warm, deliberately not the cool gray-white that every other AI brand uses. Headlines run a **slab-serif display** ("Copernicus" / Tiempos Headline) at weight 400 with negative letter-spacing, paired with **StyreneB / Inter** body sans. The combination feels like a literary publication, not a SaaS marketing page.\
\
Brand voltage comes from the **cream + coral pairing** \'97 coral (`\{colors.primary\}` \'97 #cc785c) is the signature Anthropic accent, used on every primary CTA, on the brand wordmark, and on full-bleed callout cards. The coral is warm, slightly muted, never cyan/blue \'97 a deliberate counter-positioning against OpenAI's cool slate, Google's saturated blue, and Microsoft's corporate cyan.\
\
The system has three surface modes that alternate page-by-page:\
1. **Cream canvas** (`\{colors.canvas\}`) \'97 default body floor\
2. **Light cream cards** (`\{colors.surface-card\}`) \'97 feature card backgrounds\
3. **Dark navy product surfaces** (`\{colors.surface-dark\}`) \'97 code editor mockups, model showcase cards, pre-footer CTAs, footer itself\
\
The dark surfaces are where Claude shows its product chrome \'97 code blocks, terminal output, model comparison tables, agentic-flow diagrams. The cream-to-dark contrast is the page's pacing rhythm.\
\
**Key Characteristics:**\
- Warm cream canvas (`\{colors.canvas\}` \'97 #faf9f5) with dark warm-ink text (`\{colors.ink\}` \'97 #141413). The brand's defining color choice.\
- Coral primary CTA (`\{colors.primary\}` \'97 #cc785c). Used scarcely on individual buttons, generously on full-bleed coral callout cards.\
- Slab-serif display headlines via Copernicus / Tiempos Headline at weight 400 with negative letter-spacing. Pairs with humanist sans body for a literary editorial voice.\
- Dark navy product mockup cards (`\{colors.surface-dark\}` \'97 #181715) carrying code blocks, terminal panels, model comparison data \'97 the brand shows the product chrome at scale rather than abstract marketing illustrations.\
- Light cream feature cards (`\{colors.surface-card\}` \'97 #efe9de) \'97 slightly darker than canvas, used for content-driven feature explanations.\
- Anthropic radial-spike mark \'97 a small black asterisk-like glyph (4-spoke radial) \'97 appears as the brand wordmark prefix and as a content marker.\
- Border radius is hierarchical: `\{rounded.md\}` (8px) for buttons + inputs, `\{rounded.lg\}` (12px) for content + product cards, `\{rounded.xl\}` (16px) for the hero illustration container, `\{rounded.pill\}` for badges.\
- Section rhythm `\{spacing.section\}` (96px) \'97 modern-SaaS standard. Internal card padding stays generous at `\{spacing.xl\}` (32px).\
\
## Colors\
\
### Brand & Accent\
- **Coral / Primary** (`\{colors.primary\}` \'97 #cc785c): The signature Anthropic warm coral. Used on every primary CTA background, on full-bleed coral callout cards, on the brand wordmark accent. The most-recognized Anthropic color outside of the spike-mark logo.\
- **Coral Active** (`\{colors.primary-active\}` \'97 #a9583e): The press / hover-darker variant.\
- **Coral Disabled** (`\{colors.primary-disabled\}` \'97 #e6dfd8): A desaturated cream-tinted disabled state.\
- **Accent Teal** (`\{colors.accent-teal\}` \'97 #5db8a6): Used sparingly on secondary product surfaces (terminal status indicators, "active connection" dots in connectors page).\
- **Accent Amber** (`\{colors.accent-amber\}` \'97 #e8a55a): A small companion warm-tone used on category badges and inline highlights.\
\
### Surface\
- **Canvas** (`\{colors.canvas\}` \'97 #faf9f5): The default page floor. Tinted cream \'97 warm, deliberately not pure white.\
- **Surface Soft** (`\{colors.surface-soft\}` \'97 #f5f0e8): Section dividers, very-soft band backgrounds.\
- **Surface Card** (`\{colors.surface-card\}` \'97 #efe9de): Feature cards, content cards. One step darker than canvas.\
- **Surface Cream Strong** (`\{colors.surface-cream-strong\}` \'97 #e8e0d2): A strongest-cream variant used on selected category tabs and emphasized section bands.\
- **Surface Dark** (`\{colors.surface-dark\}` \'97 #181715): Code editor mockups, model showcase cards, footer. The dominant dark surface.\
- **Surface Dark Elevated** (`\{colors.surface-dark-elevated\}` \'97 #252320): Elevated cards inside dark bands (settings panels in mockups).\
- **Surface Dark Soft** (`\{colors.surface-dark-soft\}` \'97 #1f1e1b): Slightly lighter dark, used for code block backgrounds inside larger dark cards.\
- **Hairline** (`\{colors.hairline\}` \'97 #e6dfd8): The 1px border tone on cream surfaces. Same hex as `\{colors.primary-disabled\}` \'97 borders feel like one elevation step rather than ink lines.\
- **Hairline Soft** (`\{colors.hairline-soft\}` \'97 #ebe6df): Barely-visible divider used inside the same band.\
\
### Text\
- **Ink** (`\{colors.ink\}` \'97 #141413): All headlines and primary text. Warm dark, slightly off-pure-black.\
- **Body Strong** (`\{colors.body-strong\}` \'97 #252523): Emphasized paragraphs, lead text.\
- **Body** (`\{colors.body\}` \'97 #3d3d3a): Default running-text color.\
- **Muted** (`\{colors.muted\}` \'97 #6c6a64): Sub-headings, breadcrumbs, footer-adjacent secondary text.\
- **Muted Soft** (`\{colors.muted-soft\}` \'97 #8e8b82): Captions, fine-print, copyright lines.\
- **On Primary** (`\{colors.on-primary\}` \'97 #ffffff): Text on coral buttons.\
- **On Dark** (`\{colors.on-dark\}` \'97 #faf9f5): Cream-tinted white used on dark surfaces (echoes the canvas tone).\
- **On Dark Soft** (`\{colors.on-dark-soft\}` \'97 #a09d96): Footer body text, secondary labels in dark mockups.\
\
### Semantic\
- **Success** (`\{colors.success\}` \'97 #5db872): Green status dots, "available" indicators.\
- **Warning** (`\{colors.warning\}` \'97 #d4a017): Warning callouts (rare on marketing surfaces).\
- **Error** (`\{colors.error\}` \'97 #c64545): Validation errors.\
\
## Typography\
\
### Font Family\
The system runs **Copernicus** (or **Tiempos Headline** as substitute) as the slab-serif display face for headlines, and **StyreneB** (or **Inter** as substitute) as the humanist sans for body, navigation, and UI labels. **JetBrains Mono** handles code blocks. The fallback stack walks `Tiempos Headline, Garamond, "Times New Roman", serif` for display and `Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif` for body.\
\
The display/body split is editorial:\
- Copernicus serif (weight 400, negative tracking) \uc0\u8594  h1, h2, h3, hero display\
- StyreneB sans (weight 400-500) \uc0\u8594  body, navigation, buttons, captions, labels\
- JetBrains Mono \uc0\u8594  all code blocks and terminal text\
\
### Hierarchy\
\
| Token | Size | Weight | Line Height | Letter Spacing | Use |\
|---|---|---|---|---|---|\
| `\{typography.display-xl\}` | 64px | 400 | 1.05 | -1.5px | Homepage h1 ("Meet your thinking partner") \'97 Copernicus serif |\
| `\{typography.display-lg\}` | 48px | 400 | 1.1 | -1px | Section heads \'97 Copernicus |\
| `\{typography.display-md\}` | 36px | 400 | 1.15 | -0.5px | Sub-section heads, model names \'97 Copernicus |\
| `\{typography.display-sm\}` | 28px | 400 | 1.2 | -0.3px | Pricing tier names, callout headlines \'97 Copernicus |\
| `\{typography.title-lg\}` | 22px | 500 | 1.3 | 0 | Pricing plan size labels \'97 StyreneB |\
| `\{typography.title-md\}` | 18px | 500 | 1.4 | 0 | Feature card titles, intro paragraphs |\
| `\{typography.title-sm\}` | 16px | 500 | 1.4 | 0 | Connector tile titles, list labels |\
| `\{typography.body-md\}` | 16px | 400 | 1.55 | 0 | Default running-text \'97 StyreneB |\
| `\{typography.body-sm\}` | 14px | 400 | 1.55 | 0 | Footer body, fine-print |\
| `\{typography.caption\}` | 13px | 500 | 1.4 | 0 | Badge labels, captions |\
| `\{typography.caption-uppercase\}` | 12px | 500 | 1.4 | 1.5px | Category tags, "NEW" badges |\
| `\{typography.code\}` | 14px | 400 | 1.6 | 0 | Code blocks \'97 JetBrains Mono |\
| `\{typography.button\}` | 14px | 500 | 1.0 | 0 | Standard button labels |\
| `\{typography.nav-link\}` | 14px | 500 | 1.4 | 0 | Top-nav menu items |\
\
### Principles\
Display sizes use weight 400 (regular), never bold. Negative letter-spacing (-0.3 to -1.5px) is essential \'97 Copernicus without it reads as off-brand. The serif character is what gives Anthropic its literary, considered voice; switching to a sans-serif display would make Claude feel like every other AI tool.\
\
Body type stays at weight 400 for paragraphs, weight 500 for labels and emphasized phrases. The sans body is humanist (StyreneB) \'97 never geometric. Inter is an acceptable substitute because of its similar humanist proportions; Helvetica or Arial would be too neutral and break the warm-editorial feel.\
\
### Note on Font Substitutes\
If Copernicus / Tiempos Headline is unavailable, **Cormorant Garamond** at weight 500 with -0.02em letter-spacing is the closest open-source approximation. **EB Garamond** is a fallback. For StyreneB, **Inter** is the closest match \'97 both are humanist sans designed for screen reading. **S\'f6hne** is another close alternative if licensed.\
\
## Layout\
\
### Spacing System\
- **Base unit:** 4px.\
- **Tokens:** `\{spacing.xxs\}` 4px \'b7 `\{spacing.xs\}` 8px \'b7 `\{spacing.sm\}` 12px \'b7 `\{spacing.md\}` 16px \'b7 `\{spacing.lg\}` 24px \'b7 `\{spacing.xl\}` 32px \'b7 `\{spacing.xxl\}` 48px \'b7 `\{spacing.section\}` 96px.\
- **Section padding:** `\{spacing.section\}` (96px) \'97 modern-SaaS rhythm.\
- **Card internal padding:** `\{spacing.xl\}` (32px) for feature cards, pricing tier cards, model comparison cards; `\{spacing.lg\}` (24px) for code-window cards and connector tiles.\
- **Callout / CTA bands:** `\{spacing.xxl\}` (48px) inside coral callout cards; 64px inside the larger dark CTA band.\
\
### Grid & Container\
- **Max content width:** ~1200px centered.\
- **Editorial body:** Single 12-column grid; hero often uses 6/6 split (h1 left, illustration right).\
- **Feature card grids:** 3-up at desktop, 2-up at tablet, 1-up at mobile.\
- **Connector tile grids:** 4-up or 6-up at desktop, 2-up at tablet, 1-up at mobile.\
- **Pricing grid:** 3-up at desktop (Free / Pro / Team / Enterprise often), 1-up at mobile.\
\
### Whitespace Philosophy\
The cream canvas + serif display + generous internal padding create an editorial pacing \'97 Claude reads like a long-form magazine column rather than a marketing template. Whitespace between bands stays uniform at 96px; whitespace inside cards is generous (32px), letting type breathe.\
\
## Elevation & Depth\
\
| Level | Treatment | Use |\
|---|---|---|\
| Flat | No shadow, no border | Body sections, top nav, hero bands |\
| Soft hairline | 1px `\{colors.hairline\}` border | Inputs, sub-nav, occasionally on cards |\
| Cream card | `\{colors.surface-card\}` background \'97 no shadow | Feature cards, content cards |\
| Dark surface card | `\{colors.surface-dark\}` background \'97 no shadow | Code editor mockups, model showcase cards |\
| Subtle drop shadow | Faint shadow at low alpha | Hover-elevated states (the system uses `0 1px 3px rgba(20,20,19,0.08)` rarely) |\
\
The elevation philosophy is **color-block first, shadow rare**. Most depth comes from the cream-vs-dark surface contrast. Shadows are minimal. The dark surface mockups have their own internal product chrome (code editor scrollbars, line numbers, syntax highlighting) which adds detail without needing external shadows.\
\
### Decorative Depth\
- The Anthropic spike-mark glyph (4-spoke radial asterisk) appears as a small black mark in the brand wordmark and inline as a content marker.\
- Code editor mockups carry their own internal depth: syntax-highlighted text in muted blues / oranges / grays, line numbers in `\{colors.muted-soft\}`, status bars at the bottom in `\{colors.surface-dark-elevated\}`.\
- Some hero illustrations use simple line-art with coral and dark-navy strokes on cream \'97 minimal, hand-drawn-feeling, never photorealistic.\
\
## Shapes\
\
### Border Radius Scale\
\
| Token | Value | Use |\
|---|---|---|\
| `\{rounded.xs\}` | 4px | Reserved for badge accents and tiny dropdowns |\
| `\{rounded.sm\}` | 6px | Small inline buttons, dropdown items |\
| `\{rounded.md\}` | 8px | Standard CTA buttons, text inputs, category tabs |\
| `\{rounded.lg\}` | 12px | Content cards (feature, pricing, code-window, model-comparison) |\
| `\{rounded.xl\}` | 16px | Hero illustration container, the larger marquee components |\
| `\{rounded.pill\}` | 9999px | Badge pills, "NEW" tags |\
| `\{rounded.full\}` | 9999px / 50% | Avatar substitutes, icon buttons |\
\
### Photography & Illustrations\
Claude's hero rarely uses photography. Instead it uses:\
- Simple line-art illustrations with coral + dark-navy strokes on the cream canvas\
- Code editor mockups (the dominant "hero" treatment on developer-focused pages)\
- Terminal output mockups with monospace text on dark\
- Model comparison cards (Opus / Sonnet / Haiku) with abstract geometric thumbnails\
\
When photography is used (rare \'97 mostly testimonials), avatars crop to perfect circles at 40px diameter.\
\
## Components\
\
### Top Navigation\
\
**`top-nav`** \'97 Cream nav bar pinned to the top of every page. 64px tall, `\{colors.canvas\}` background. Carries the Anthropic spike-mark + "Claude" wordmark at left, primary horizontal menu (Product, Solutions, Use Cases, Pricing, Research, Company) center-left, right-side cluster with "Sign in" text-link, "Try Claude" `\{component.button-primary\}` (coral). Menu items in `\{typography.nav-link\}` (StyreneB 14px / 500).\
\
### Buttons\
\
**`button-primary`** \'97 The signature coral CTA. Background `\{colors.primary\}` (#cc785c), text `\{colors.on-primary\}` (white), type `\{typography.button\}` (StyreneB 14px / 500), padding 12px \'d7 20px, height 40px, rounded `\{rounded.md\}` (8px). Active state `button-primary-active` darkens to `\{colors.primary-active\}` (#a9583e).\
\
**`button-secondary`** \'97 Cream button with hairline outline. Background `\{colors.canvas\}`, text `\{colors.ink\}`, 1px hairline border, same padding + height + radius as primary.\
\
**`button-secondary-on-dark`** \'97 Used over `\{colors.surface-dark\}` cards. Background `\{colors.surface-dark-elevated\}` (#252320), text `\{colors.on-dark\}`. Stays dark \'97 the system never inverts to a light secondary on dark surfaces.\
\
**`button-text-link`** \'97 Inline text button, no background. Used for "Sign in" in the top nav and inline CTA links.\
\
**`button-icon-circular`** \'97 36px circular icon button. Background `\{colors.canvas\}`, hairline border, ink-color icon. Used for carousel arrows, share, "view more".\
\
**`text-link`** \'97 Inline body links in `\{colors.primary\}` (the coral). Underlined on press; the coral inline link is one of the system's most distinctive small details.\
\
### Cards & Containers\
\
**`hero-band`** \'97 Cream-canvas hero with a 6-6 grid: h1 + sub-headline + button row on the left, hero illustration card or product mockup card on the right. Vertical padding `\{spacing.section\}` (96px).\
\
**`hero-illustration-card`** \'97 A larger card holding the hero's right-side artifact \'97 sometimes a coral-stroke line illustration on cream background, sometimes a dark code editor mockup. Background `\{colors.canvas\}` or `\{colors.surface-dark\}` depending on context, rounded `\{rounded.xl\}` (16px).\
\
**`feature-card`** \'97 Used in 3-up feature grids. Background `\{colors.surface-card\}` (#efe9de \'97 slightly darker cream), rounded `\{rounded.lg\}` (12px), internal padding `\{spacing.xl\}` (32px). Carries a small icon at top, an `\{typography.title-md\}` headline, and a body description in `\{typography.body-md\}`.\
\
**`product-mockup-card-dark`** \'97 Dark navy card showing actual Claude product chrome (chat interface, code editor, agent controls). Background `\{colors.surface-dark\}`, rounded `\{rounded.lg\}`, internal padding `\{spacing.xl\}` (32px). Carries text labels in `\{colors.on-dark\}` and product UI fragments below.\
\
**`code-window-card`** \'97 A specialized dark card showing a code editor with line numbers, syntax-highlighted code in `\{typography.code\}` (JetBrains Mono), and sometimes a "Run" button or terminal output panel below. Background `\{colors.surface-dark\}` with `\{colors.surface-dark-soft\}` for the inner code block, rounded `\{rounded.lg\}`, padding `\{spacing.lg\}` (24px). The signature visual element of Claude Code product pages.\
\
**`model-comparison-card`** \'97 Used on the homepage's "Which problem are you up against?" section comparing Opus / Sonnet / Haiku. Background `\{colors.canvas\}` with hairline border, rounded `\{rounded.lg\}`, internal padding `\{spacing.xl\}` (32px). Carries the model name, a short capability blurb, and a `\{component.text-link\}` to learn more.\
\
**`pricing-tier-card`** \'97 Standard tier card. Background `\{colors.canvas\}` with hairline border, rounded `\{rounded.lg\}`, padding `\{spacing.xl\}` (32px). Carries the plan name in `\{typography.title-lg\}` (StyreneB), price in `\{typography.display-sm\}` (Copernicus serif!), feature checklist in `\{typography.body-md\}`, and a `\{component.button-primary\}` at the bottom.\
\
**`pricing-tier-card-featured`** \'97 The featured tier (typically "Pro" or "Team"). Background flips to `\{colors.surface-dark\}`, text inverts to `\{colors.on-dark\}`. The dark surface IS the featured-tier signal.\
\
**`callout-card-coral`** \'97 A full-bleed coral card carrying a major call-to-action. Background `\{colors.primary\}` (#cc785c), text `\{colors.on-primary\}` (white), rounded `\{rounded.lg\}`, padding `\{spacing.xxl\}` (48px). The coral surface IS the voltage; the CTA inside uses an inverted button style (cream/canvas button on coral).\
\
**`connector-tile`** \'97 Used on the connectors page's integration grid. Background `\{colors.canvas\}` with hairline border, rounded `\{rounded.lg\}`, padding 20px. Each tile carries a logo at top, a `\{typography.title-sm\}` connector name, and a short description.\
\
### Inputs & Forms\
\
**`text-input`** \'97 Standard text input. Background `\{colors.canvas\}`, text `\{colors.ink\}`, type `\{typography.body-md\}`, rounded `\{rounded.md\}` (8px), padding 10px \'d7 14px, height 40px. 1px hairline border in `\{colors.hairline\}`.\
\
**`text-input-focused`** \'97 Focus state. Border thickens or shifts to `\{colors.primary\}` (coral) for emphasis. Carries a 3px coral-at-15%-alpha outer ring.\
\
**`cookie-consent-card`** \'97 Bottom-right floating dark cookie banner. Background `\{colors.surface-dark\}`, text `\{colors.on-dark\}`, rounded `\{rounded.lg\}`, padding `\{spacing.lg\}` (24px). One of the few places dark surface appears at small scale on cream pages.\
\
### Tags / Badges\
\
**`badge-pill`** \'97 Small pill label used for category tags. Background `\{colors.surface-card\}`, text `\{colors.ink\}`, type `\{typography.caption\}` (13px / 500), rounded `\{rounded.pill\}`, padding 4px \'d7 12px.\
\
**`badge-coral`** \'97 Coral-fill badge for "NEW", "BETA", featured highlights. Background `\{colors.primary\}`, text `\{colors.on-primary\}`, type `\{typography.caption-uppercase\}` (12px / 500 / 1.5px tracking), rounded `\{rounded.pill\}`, padding 4px \'d7 12px.\
\
### Tab / Filter\
\
**`category-tab`** + **`category-tab-active`** \'97 Used in sub-nav rows on solutions / connectors pages. Inactive: transparent background, `\{colors.muted\}` text. Active: `\{colors.surface-card\}` background, `\{colors.ink\}` text. Padding 8px \'d7 14px, rounded `\{rounded.md\}`.\
\
### CTA / Footer\
\
**`cta-band-coral`** \'97 A pre-footer "Try Claude" CTA card. Full-width coral fill, white type, rounded `\{rounded.lg\}`, padding 64px. Carries an h2 in `\{typography.display-sm\}` (still serif!), a sub-line, and a cream-button CTA.\
\
**`cta-band-dark`** \'97 Alternative pre-footer band on developer-focused pages. Background `\{colors.surface-dark\}`, text `\{colors.on-dark\}`, rounded `\{rounded.lg\}`, padding 64px. Often pairs with a code-window card.\
\
**`footer`** \'97 Dark navy footer that closes every page. Background `\{colors.surface-dark\}` (#181715), text `\{colors.on-dark-soft\}`. 4-column link list at desktop covering Product / Company / Resources / Legal. Vertical padding 64px. The Anthropic spike-mark + "Anthropic" wordmark sits at the top in `\{colors.on-dark\}`. The footer never inverts.\
\
## Do's and Don'ts\
\
### Do\
- Anchor every page on the cream canvas. Pure white reads as "any other AI tool"; the warm tint is the brand differentiator.\
- Use Copernicus serif for every display headline. Pair with StyreneB sans body. Negative letter-spacing on display sizes is non-negotiable.\
- Reserve `\{colors.primary\}` (coral) for primary CTAs and full-bleed `\{component.callout-card-coral\}` moments. Don't paint accent moments coral elsewhere.\
- Use `\{component.product-mockup-card-dark\}` and `\{component.code-window-card\}` to show actual Claude product chrome. Don't paint marketing illustrations of code when you can show real code.\
- Pair `\{component.feature-card\}` (cream) with `\{component.product-mockup-card-dark\}` (navy) in alternating bands. The cream-to-dark rhythm is the brand's pacing mechanism.\
- Use the Anthropic spike-mark glyph as the brand wordmark prefix. Never invert the mark to white-on-dark within the wordmark itself.\
- Apply `\{spacing.section\}` (96px) between major bands.\
\
### Don't\
- Don't use cool grays or pure white for canvas. Cream is the brand.\
- Don't bold serif display weight. Copernicus at 700 reads as bombastic; the system stays at 400.\
- Don't use cool blue or saturated cyan as a brand accent. The coral is the brand voltage.\
- Don't put coral everywhere. The coral is scarce on individual elements and generous only on full-bleed coral callout cards.\
- Don't use Inter for display headlines. The serif character is the brand voice.\
- Don't repeat the same surface mode in two consecutive bands. The pacing alternates: cream \uc0\u8594  cream-card \u8594  dark-mockup \u8594  cream \u8594  coral-callout \u8594  dark-footer.\
- Don't add hover state styling beyond what the system already encodes \'97 primary darkens on press; nothing else changes.\
\
## Responsive Behavior\
\
### Breakpoints\
\
| Name | Width | Key Changes |\
|---|---|---|\
| Mobile | < 768px | Hamburger nav; hero h1 64\uc0\u8594 32px; hero-illustration-card stacks below content; feature grids 1-up; connector tiles 2-up; pricing 1-up; footer 4 cols \u8594  1 |\
| Tablet | 768\'961024px | Top nav stays horizontal but tightens; feature cards 2-up; connector tiles 3-up; pricing 2-up |\
| Desktop | 1024\'961440px | Full top-nav with all menu items; 3-up feature cards; 4-up or 6-up connector tiles; 3-up pricing tiers |\
| Wide | > 1440px | Same as desktop with more outer breathing room; max content width caps at 1200px |\
\
### Touch Targets\
- `\{component.button-primary\}` at minimum 40 \'d7 40px.\
- `\{component.button-icon-circular\}` at exactly 36 \'d7 36 \'97 slightly under WCAG 44 but visually centered.\
- `\{component.text-input\}` height is 40px.\
- Connector tile entire card area is tappable; effective tap area >> 44px.\
\
### Collapsing Strategy\
- Top nav collapses to hamburger at < 768px; menu opens as a full-screen cream sheet.\
- Hero band's 6-6 grid collapses to single-column on mobile \'97 h1 + sub-head + buttons first, then the illustration / mockup card below.\
- Feature grids reduce columns rather than scaling cards down.\
- Pricing tier cards collapse 4 \uc0\u8594  2 \u8594  1; featured-tier dark surface stays visually distinct at every breakpoint.\
- Code-window cards retain code legibility at every breakpoint by allowing horizontal scroll within the card rather than wrapping code lines.\
\
### Image Behavior\
- Code blocks inside dark mockups stay at fixed font-size; horizontal scroll on mobile rather than wrapping.\
- Hero illustrations scale proportionally; line-art strokes thin slightly on mobile.\
- Avatar photos in testimonials crop to circles at every breakpoint.\
\
## Iteration Guide\
\
1. Focus on ONE component at a time. Reference its YAML key (`\{component.feature-card\}`, `\{component.code-window-card\}`).\
2. Variants of an existing component (`-active`, `-disabled`, `-focused`) live as separate entries in `components:`.\
3. Use `\{token.refs\}` everywhere \'97 never inline hex.\
4. Never document hover. Default and Active/Pressed states only.\
5. Display headlines stay Copernicus serif 400 with negative tracking. Body stays StyreneB / Inter 400. The split is unbreakable.\
6. Cream + coral + dark navy is the trinity. Don't introduce a fourth surface tone (no purple cards, no green sections).\
7. When in doubt about emphasis: bigger Copernicus serif before bolder weight.\
\
## Known Gaps\
\
- Copernicus and StyreneB are licensed Anthropic typefaces and not available as public web fonts. Substitutes (Tiempos Headline / Cormorant Garamond / EB Garamond for serif; Inter / S\'f6hne for sans) are documented in the typography section.\
- The Anthropic radial-spike-mark is a brand glyph rendered as inline SVG; it's not formalized as a system token here. Treat it as a logo asset.\
- Animation and transition timings (chat message reveal, code block typewriter effect on the homepage, agentic-flow diagram animations) are not in scope.\
- Form validation states beyond `\{component.text-input-focused\}` are not extracted \'97 error / success states would need a sign-up or feedback flow to confirm.\
- The actual Claude product surface (claude.ai chat interface) shares some tokens with the marketing site but adds many product-specific components (chat bubbles, message tools, file upload chips, conversation history sidebar) that are out of scope for this marketing-surface document.\
- The "agent" / "computer use" demo cards on certain pages display animated Claude controlling a browser \'97 the static screenshot doesn't fully capture the animation chrome.\
}