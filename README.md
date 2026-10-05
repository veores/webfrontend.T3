# Side B Records - Music Store Website

Midterm project: a multi-page responsive website built with HTML5, CSS3 and Bootstrap 5.

**Author:** Bekarys Zharylgassyn
**Live site:** _add your GitHub Pages / Netlify link here_

## Topic
Side B is a fictional independent music shop that sells vinyl records, CDs and turntables. Titles and artists are invented.

## Pages
| File | Purpose |
|------|---------|
| `index.html` | Home: hero, format categories, new arrivals, shop info |
| `vinyl.html` | Vinyl product grid and a condition-grade table |
| `cds.html` | CD product grid and reasons to buy CDs |
| `turntables.html` | Turntable cards and a comparison table |
| `contact.html` | Reservation form, address and opening hours |

## Features
- Semantic HTML5: `header`, `nav`, `main`, `section`, `article`, `aside`, `address`, `footer`
- Navigation bar on every page, current page highlighted
- Headings, paragraphs, lists, links, local SVG images with `alt` text
- Two tables (grading guide, turntable comparison) and one form (reservation)
- CSS: custom properties, element/class/ID selectors, consistent colours, fonts, spacing
- Flexbox: hero, product cards, footer. Grid: product grid (4/3/2 columns), info block
- Positioning: `relative` hero with `absolute` badge, `fixed` back-to-top button, `sticky` header
- Media queries for tablet (max 992px) and mobile (max 576px)
- Bootstrap 5 grid (`row`, `col-*`, `row-cols-*`) and utilities (spacing, buttons, text alignment, containers)

## Structure
```
index.html  vinyl.html  cds.html  turntables.html  contact.html
css/style.css
images/*.svg
```

## Publish
- **GitHub Pages:** push the folder to a repository, then Settings > Pages > deploy from `main` / root.
- **Netlify:** drag the project folder onto https://app.netlify.com/drop.
