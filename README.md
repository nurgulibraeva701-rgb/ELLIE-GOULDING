# Ellie Goulding — Brightest Blue

A responsive album page for **Brightest Blue** by Ellie Goulding, built with HTML and CSS. It is a practice recreation of the release page layout from [Monstercat](https://www.monstercat.com/release/MCLP017), adapted to a different album.

**Live demo:** https://nurgulibraeva701-rgb.github.io/ELLIE-GOULDING/

## Preview
<img width="1464" height="2950" alt="C2-Monstercat-2" src="https://github.com/user-attachments/assets/9d8dbebc-26a3-45b7-ac41-eac8b2fa5649" />


## Features

- **Hero section** with a background image, album cover, vertical release-date label, outlined title and "Listen now" / "Share" buttons
- **Track list** of all 16 tracks with automatic numbering using CSS counters, play and share buttons, track durations and a hover highlight
- **Music video section** with an embedded YouTube player that keeps a 16:9 ratio
- **Footer** with links and copyright information
- **Responsive design:** on screens narrower than 800px the hero stacks vertically and the track list and footer switch to a compact layout

## Technologies

- HTML5
- CSS3 (Flexbox, Grid, CSS variables, counters, media queries, `aspect-ratio`)
- Google Fonts: Montserrat and Syncopate
- Font Awesome (icons)
- GitHub Pages (hosting)

## Project structure

```
ELLIE-GOULDING/
├── index.html
├── style.css
├── README.md
└── img/
    ├── cover.jpg   # album cover
    └── bg.jpg      # hero background
```

## How to run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/nurgulibraeva701-rgb/ELLIE-GOULDING.git
   ```
2. Open the project folder.
3. Open `index.html` in your browser.

No installation or build step is needed.

## What I practiced

- Building a page layout from an existing design
- Positioning with Flexbox and Grid
- Styling text with outlines and custom fonts
- Using CSS variables to keep colors consistent
- Making a page responsive with media queries
- Embedding external content (YouTube) responsively
- Publishing a site with GitHub Pages

## Disclaimer

This is an educational project and is not affiliated with Monstercat, Ellie Goulding or Polydor Records. The album artwork, track names and music video belong to their respective owners. The layout is inspired by the Monstercat release page.
