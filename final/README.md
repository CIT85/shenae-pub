# Project
## Selecting A Topic
I would like to build a website that explains the deep water trench that runs along the central coast of California, specifically through Big Sur, and the different types of whale migrations and behaviors that are on display because of that. 
## Why Choose This Topic
I chose this topic because I am lucky enough to whitness this spectacular phenomenon for weeks at a time, over the course of the last 15 years. Also, as a local, I am constantly asked by visitors and tourists about the whales. 
## AI Prompts & Content
### ChatGPT Prompt:
 -  "I want to create a website depicting the most interesting facts about the whale migrations that are visible from te Big Sur Coast due to the deep water trench that's right off shore. I want to make a table that has species, pod sizes, and direction of travel. what other interesting facts could I include in my table?"
### ChatGPT Response:
-  Speed (mph), Main Feeding Area, Main Calving Area, Conservation Status, Preferred Depth Range 
        -
### ChatGPT Prompt: 
- "What could be a good title and introduction for my page? I want it to be poetic and mysterious."
### ChatGPT Response: 
- Title: *Where the Earth Falls Away*

- Intro: Beneath the cliffs of Big Sur lies a hidden world — a submarine canyon deeper than the Grand Canyon itself. In its cold, shadowed corridors, ancient whales pass in silence, tracing migration paths older than human memory. This site is a journey beneath the waves

- Through the deepwater trench, along the whales’ long road, and into the heart of one of the planet’s most mysterious coasts.

## I've also used Fotor Photo Editor to make certain images Black & White

## Towards the end, I ran all pages (individually) through ChatGPT along with our assignment prompt to make sure I was meeting all requirements

# Menu Text
- **Home**- An introduction about the deep water trench that runs along the coast, about the feeding grounds for the whales, their breeding and feeding migrations, and the behaviors that can be seen from the coast of Big Sur

## **Species** 
Their unique characteristics, breeding cycle, food supply, and notable behaviors:
    - Humpbacks
    - Grey Whales
    - Blue Whales
    - Orcas 
- **Migration Calendar** with species and pod sizes, migration distance, and direction of travel
- **Unique Encounters**interesting stories and unique occurances on California's Central Coast. 
- **Sitemap**

      MY TODO LIST
<---------------------->
[x]Fix broken links on species.html

[x]Add color palette

[x]Add migration table to nav on all pages

[x]Fix Species Details list heading and spacing on all 4 species pages

[x]Fix active status on nav on blue_whales.html page

[x]Move copyright to bottom of page on all pages

[x]Stack sitemap, back to top, BSCC, ChatGPT in footer on all pages

# Color Palette 
- #000 black: Background on all pages
- #050505, #0c0c0c, #181818: lighter or more gradient blacks: table backgrounds and stripe colors
- #045d6d dark teal: Accent used for borders, table headers, and hover effects 
- #35f0ff neon accent: highlights active links and important ui elements
- #6cf5ff, #a7f8ff secondary accent: used accross headings and some elements

## Typography link is in the index.html

# Typography Enhancements
For typography, I set a consistent base font on the body using "Didact Gothic", sans-serif. I styled headings (h1–h4) with different font sizes and accent colors to create a clear hierarchy. I also added text-transform and letter-spacing on headings for emphasis. All links include hover, focus, and visited states for accessibility, and the same typography styles appear on all pages using only element and class selectors (no inline styles or IDs).

# Decorative or Positional Enhancements
I used three types of CSS positioning for decorative/interactive elements:
-	a sticky header that stays at the top while scrolling,
-	a fixed Back-to-Top button in the bottom-right corner, and
-	an absolute-positioned aside callout inside a section.

These positioned elements help highlight important information and improve navigation while staying within the allowed CSS for Phase 2.

## I used *flexbox* in the header and nav, *multicolumn* for text, *grid* for the color palette and important_info page and *media queries* at **601-899 and 900+**
- changed my media queries to 481 and 768 to satisfy the standards reccomended by Dave Gray. 

## Added businesses.html (Big Sur Map) to site
[x] add to all navigation<br>
[x] add to sitemap page 

## Hero Image Design
I chose a wide, dramatic aerial photograph of the Big Sur coastline for my hero image because it reflects the tone and theme of the website. The cliffs and ocean also visually connect to the whale migrations described throughout the site.

The hero image appears at the top of my index.html page in a full-width banner. I used `background-size: cover` so the image always fills the hero section, regardless of device or screen size. I set `background-position: center` to keep the cliffs and coastline framed correctly as the page scales.

To ensure readability of the overlaid text, I added a semi-transparent dark overlay using the `::before` pseudo-element. The text is centered and uses high-contrast white for accessibility. This layout choice helps the hero section feel balanced while maintaining a strong visual impact.