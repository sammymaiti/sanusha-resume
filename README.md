# Sanusha K B — Resume Website

A responsive resume website built with plain HTML and CSS (no JavaScript) and published with GitHub Pages.

**Live site:** https://sammymaiti.github.io/sanusha-resume/

## Sections
- **About** – headline, career objective and a short facts row
- **Education** – BBA in Digital Business and Entrepreneurship (BBA DBE), IIM Bangalore; St Claret Pre-University College; St Mary's Public School
- **Experience** – Co-founder & COO, Centurion Robotics; HR Intern (Recruitment), SocioBlend
- **Projects** – running operations at Centurion Robotics, and this website
- **Skills** – operations, people, ways of working, digital, and languages

## CSS highlights
- Flexbox navigation bar with an Auto / Light / Dark theme switch built from radio buttons and `:has()`
- Colours defined once with `light-dark()`: rose pink and navy in light mode, black and light pink in dark mode; every text colour passes WCAG AA
- Hero headline that rises into place line by line on load
- Cards show a short front; the detail slides up on hover, or opens in place on tap (`@media (hover: none)`); front and detail share one grid cell so nothing overflows
- Scroll-driven animations: scroll-spy navigation (`timeline-scope` + view timelines), a reading-progress line, the hero name narrowing along Archivo's width axis, and a fade on the phone nav row
- Section rail layout with CSS Grid, a bento grid for projects, and a container query on the experience cards
- Element, class and ID selectors, each group labelled in `style.css`
- Reduced-motion support and a print stylesheet that shows all the hidden detail
