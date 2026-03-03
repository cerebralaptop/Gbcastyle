# GBCA Brand Style Guide
## Extracted from www.gbca.org.au — February 2026

---

## 1. Color Palette

### Primary Colors

| Name             | Hex       | RGB              | Usage                                              |
|------------------|-----------|------------------|-----------------------------------------------------|
| GBCA Green       | `#44883E` | `68, 136, 62`    | H2 headings, section titles, icon circle backgrounds |
| GBCA Lime        | `#78BE21` | `120, 190, 33`   | Primary CTA buttons, H3 headings, accent highlights  |
| GBCA Navy        | `#005687` | `0, 86, 135`     | H4 subheadings, stat numbers, secondary emphasis      |

### Secondary / Supporting Colors

| Name             | Hex       | RGB              | Usage                                              |
|------------------|-----------|------------------|-----------------------------------------------------|
| Slide Green      | `#229C47` | `34, 156, 71`    | Hero carousel slide backgrounds                     |
| Light Green Tint | `#F5FFF4` | `245, 255, 244`  | Subtle green background sections                     |
| Light Gray       | `#EEF0F5` | `238, 240, 245`  | Search bar background, input fields                  |

### Neutral Colors

| Name             | Hex       | RGB              | Usage                                              |
|------------------|-----------|------------------|-----------------------------------------------------|
| Near Black       | `#0A0202` | `10, 2, 2`       | Body text, default paragraph color                   |
| Dark Gray        | `#303030` | `48, 48, 48`     | Navigation link text                                 |
| Charcoal         | `#272425` | `39, 36, 37`     | Footer text                                          |
| White            | `#FFFFFF` | `255, 255, 255`  | Page backgrounds, button text, hero overlay text     |
| Mid Gray         | `#BBBBBB` | `187, 187, 187`  | Inactive carousel slide backgrounds                  |

### Overlay Colors

| Name             | Value                   | Usage                         |
|------------------|-------------------------|-------------------------------|
| Dark Overlay     | `rgba(22, 22, 22, 0.5)` | Hero image overlays          |
| Light Overlay    | `rgba(255, 255, 255, 0.33)` | Light section overlays   |
| Semi-Black       | `rgba(0, 0, 0, 0.5)`   | Image overlays               |

---

## 2. Typography

### Font Families

| Role             | Font                                                        | Fallbacks                              |
|------------------|-------------------------------------------------------------|----------------------------------------|
| **Primary**      | `Roboto`                                                    | `sans-serif`                           |
| **UI / Buttons** | `Roboto Condensed`                                          | `Helvetica Neue`, `Arial`, `sans-serif`|

> Both fonts are loaded from Google Fonts.

### Heading Styles

| Element | Size   | Weight     | Color                  | Font    | Line Height | Usage                              |
|---------|--------|------------|------------------------|---------|-------------|-------------------------------------|
| **H1**  | 40px   | 700 (Bold) | `#FFFFFF` (white)      | Roboto  | 40px        | Page titles on hero banners         |
| **H2**  | 42px   | 100 (Thin) | `#44883E` (GBCA Green) | Roboto  | 50px        | Section titles, lead intro text     |
| **H3**  | 28px   | 700 (Bold) | `#44883E` or `#78BE21` | Roboto  | Normal      | Sub-section titles (varies by page) |
| **H4**  | 20px   | 700 (Bold) | `#005687` (Navy)       | Roboto  | Normal      | Content subheadings                 |

### Body Text

| Element     | Size   | Weight | Color      | Line Height | Font             |
|-------------|--------|--------|------------|-------------|------------------|
| Paragraph   | 16px   | 400    | `#0A0202`  | 27.2px (1.7em) | Roboto, sans-serif |
| Footer text | 13.6px | 400    | `#272425`  | Normal      | Roboto, sans-serif |

---

## 3. Buttons

### Primary Button (CTA)

```
Background:    #78BE21 (GBCA Lime)
Text Color:    #FFFFFF (White)
Font:          Roboto Condensed, Helvetica Neue, Arial, sans-serif
Font Size:     16px
Font Weight:   400
Border Radius: 5px
Padding:       12px
Border:        2px solid transparent
```

**Hover state:** Slightly darkened background (standard darken effect)

### Button Sizing (Elementor-based)

- Standard padding: `12px` all around
- Full-width buttons are used for download CTAs
- Rounded corners: `5px` border radius consistently

---

## 4. Navigation

### Top Navigation Bar

```
Background:     #FFFFFF (White)
Position:       Fixed / Floating header
Shadow:         Subtle drop shadow on scroll
```

### Navigation Links

```
Font:           Roboto Condensed
Font Size:      16px (desktop)
Font Weight:    400
Color:          #303030 (Dark Gray)
Text Transform: None (natural case, but menu items display in UPPERCASE in design)
Hover:          Standard color shift
```

### Breadcrumbs

```
Text Color:     #FFFFFF (White, on hero banner overlay)
Text Transform: UPPERCASE
Link Style:     No underline
Separator:      ">" chevron
```

---

## 5. Links

### Content Links

```
Color:          #000000 (Black)
Text Decoration: None (no underline by default)
Font Weight:    400
```

### "Learn more >" / "Read more >" Links

```
Color:          #000000 (Black)
Text Decoration: None
Style:          Text followed by ">" character
Font Weight:    400
Font Size:      16px
```

### Footer Links

```
Color:          #272425 (Charcoal)
Text Decoration: None
Font Weight:    400
```

---

## 6. Layout & Spacing

### Page Structure

- **Max content width:** ~1200px centered container
- **Grid:** 4-column layout for feature cards (Rate, Educate, Advocate, Collaborate)
- **2-column layout** for content + sidebar sections
- **Built with:** Elementor page builder on WordPress (Agend theme)

### Sections

- Sections alternate between white backgrounds and colored backgrounds
- Green sections (`#44883E`) use white text
- Light green tint sections (`#F5FFF4`) provide subtle visual breaks
- Statistics sections use light gray (`#EEF0F5`) background

### Spacing Patterns

- Large vertical padding between major sections
- Content sections have generous white space
- Cards use consistent internal padding

---

## 7. Iconography

### Pillar Icons (Rate, Educate, Advocate, Collaborate)

```
Shape:          Circle
Background:     #44883E (GBCA Green)
Icon Color:     #FFFFFF (White)
Icon Style:     Line art / outline style
Size:           ~150px diameter
```

### Social Media Icons (Footer)

```
Style:          Circular with dark fill
Platforms:      LinkedIn, Instagram, YouTube
Color:          Dark gray/black
```

### Back-to-Top Button

```
Shape:          Circle
Background:     #44883E (GBCA Green)
Icon:           White upward arrow
Position:       Fixed, bottom-right corner
Border Radius:  50%
```

---

## 8. Hero / Banner Sections

### Homepage Carousel

```
Type:           Full-width image slider (Swiper-based)
Overlay:        Dark semi-transparent overlay for text legibility
Background:     #229C47 (fallback green) with background images
Navigation:     Left/right arrow controls, dot pagination
```

### Interior Page Banners

```
Type:           Full-width hero image with overlay
Text:           White H1 page title
Breadcrumbs:    Uppercase white links above the title
Overlay:        Semi-transparent dark overlay
```

---

## 9. Statistics / Counter Section

```
Number Size:    69px
Number Weight:  600 (Semi-Bold)
Number Color:   #005687 (GBCA Navy)
Font:           Roboto, sans-serif
Label Size:     16px (standard body)
Label Color:    Standard body text color
Background:     Light / White section
```

---

## 10. Footer

```
Background:     White / Light (transparent)
Text Color:     #272425 (Charcoal)
Font Size:      13.6px
Heading Weight: 700 (Bold) — "Quick links", "Follow us"
Link Color:     #272425
Link Style:     No underline
Layout:         Links on left, social icons on right
Copyright:      Bottom of footer, same color/size
```

---

## 11. Quick Reference — CSS Variables

```css
:root {
  /* Primary Colors */
  --gbca-green:        #44883E;
  --gbca-lime:         #78BE21;
  --gbca-navy:         #005687;

  /* Secondary Colors */
  --gbca-slide-green:  #229C47;
  --gbca-light-green:  #F5FFF4;
  --gbca-light-gray:   #EEF0F5;

  /* Neutrals */
  --gbca-near-black:   #0A0202;
  --gbca-dark-gray:    #303030;
  --gbca-charcoal:     #272425;
  --gbca-white:        #FFFFFF;
  --gbca-mid-gray:     #BBBBBB;

  /* Typography */
  --font-primary:      'Roboto', sans-serif;
  --font-ui:           'Roboto Condensed', 'Helvetica Neue', Arial, sans-serif;

  /* Sizing */
  --body-font-size:    16px;
  --body-line-height:  1.7;
  --h1-size:           40px;
  --h2-size:           42px;
  --h3-size:           28px;
  --h4-size:           20px;

  /* Components */
  --btn-radius:        5px;
  --btn-padding:       12px;
  --content-max-width: 1200px;
}
```

---

## 12. Logo

- **Mark:** Green diamond/arrow icon (Green Star symbol)
- **Wordmark:** "Green Building Council Australia" in dark text
- **Placement:** Top-left of navigation bar
- **Background:** Used on white background in the header

---

*Style guide generated by reviewing www.gbca.org.au on 20 February 2026.*
