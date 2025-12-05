## 1. Major Page Sections
- **`<header>`**
  - Site title: **“The Passage of Giants”**
  - Primary navigation (`<nav>` with `<ul>`):
    - Home  
    - Species  
      - Humpbacks  
      - Gray Whales  
      - Blue Whales  
      - Orcas  
    - Migration Table
    - Big Sur Businesses
- **`<main>`**
  - **Section 1 — “The Trench and the Travelers”**
    - `<h2>`: The Trench and the Travelers  
    - `<article>`: Overview narrative
      - Intro paragraph about trench + whales
      - Floated hero figure:
        - Humpback tail image + figcaption
      - “You’ll Find on This Page” subheading
      - `<ul>` (what’s on this page)
      - “When to Look” subheading + `<time>` elements
      - Lunge-feeding img
      - External links to NOAA and MBARI
      - Orca pair img
  - **Section 2 — “Migration at a Glance”**
    - `<h2>`: Migration at a Glance
    - `<article>`:
      - `<h3>`: Species, Length, Weight, Season, and Annual Distance
      - `<table>` with caption, thead, tbody, tfoot
  - **Section 3 — “Watching from Shore”**
    - `<h2>`: Watching from Shore
    - `<article>`:
      - `<h3>`: Quick Tips & FAQs
      - Three `<details>` / `<summary>` FAQ items:
        - Best places to watch?
        - What behavior should I look for?
        - Safety & etiquette?
- **`<footer>`**
  - Link to `site.html` (Site Map & Color Palette)
  - Credits:
    - ChatGPT
    - Fotor Image Editor
    - Big Sur Chamber of Commerce
  - Copyright line:
    - `© 2025 The Passage of Giants — Shena Ellis`
    - “Back to Top” anchor link

---

## 2. Section Organization (Hierarchy & Flow)

High-level flow:

- **Page**
  -  **Header** container [*flexbox: header title and nav alignment*]
    -  Site title (`<h1>`)
    -  Primary nav (`<nav>` + list of links) [*Flexbox: horizontal nav list with responsive wrapping*]
  -  **Main**
    -  Section 1: “The Trench and the Travelers”
      -  Article: Overview narrative
        -  Hero paragraph
        -  Hero image (humpback tail)
        -  “You’ll Find on This Page” list
        -  “When to Look” text with `<time>`
        -  Lunge-feeding image
        -  NOAA + MBARI external links
        -  Orca pair image
    -  Section 2: “Migration at a Glance”
      -  Article:
        -  Heading
        -  Migration table
    -  Section 3: “Watching from Shore”
      -  Article:
        -  Heading
        -  FAQ `<details>` items [*Flexbox: FAQ cards layout*]
  -  **Footer**
    -  Site map link
    -  Credits & external resource link
    -  Year + Back to Top link

Alternate “layout” view:

- **Header (top)**
  - [Logo/Title] ←→ [Nav links]
- **Main**
  - **Block 1**: Overview (text + images)
  - **Block 2**: Migration table (full width)
  - **Block 3**: FAQs (stacked cards)
- **Footer (bottom)** [*Flexbox: footer content alignment + spacing*]
  - Site Map | Credits | Resources | Back to Top

## Phase 4 Media Query and Responsive Behavior Plan
### Breakpoints
-  4 species pages maintain similar structures
    - humpbacks.html
    - gray_whales.html
    - blue_whales.html
    - orcas.html
- **Small screens (phones)**: `@media (max-width: 600px)`
  - Single-column layout
  - Floated/side-by-side items stack
  - Text stays readable with comfortable padding
- **Medium screens (small tablets)**: `@media (min-width: 601px) and (max-width: 899px)`
  - Main content centered with max-width
  - Some two-column patterns start to appear
- **Large screens (tablets in landscape + desktop)**: `@media (min-width: 900px)`
  - Full Flexbox + multi-column layouts
  - More white space around content
  
### migration_table.html
- Small screens
    - single-column main content
    - main migration table full width: horizontal scroll if necessary
- Medium/Large screens
    - centered table 960px main content width
    - floated image and text flow together 


---

## Site Map Page (`site.html`)

- **Small screens**
  - Color swatches and site map lists stack in a single column
  - Callout box (`Monterey Canyon` aside) appears as a normal block above or below the paragraph

- **Medium & large screens**
  - Color swatches can use a multi-column layout (Grid)
  - Callout box sits beside the text as a highlighted note

---

## Important Info Page (`important_info.html`)

- **Small screens**
  - Intro section (`.info-grid`) stacks: text first, image second
  - Safe practices and supplies content appear in a single column

- **Medium & large screens**
  - `.info-grid` uses two columns:
    - Left: warning text
    - Right: cliff/highway image and caption

## Breakout Standard
- the breakout standard I used was the standard breakout standard of 481 and 768

## Added businesses.html 



