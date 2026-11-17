# Sanusha K B — Resume Website

A responsive resume website built with plain HTML and CSS and published with GitHub Pages.

**Live site:** https://sammymaiti.github.io/sanusha-resume/

## Sections
- **About** – profile and career objective
- **Education** – BBA in Digital Business and Entrepreneurship (BBA DBE), IIM Bangalore; St Claret Pre-University College; St Mary's Public School
- **Experience** – Co-founder & COO, Tritonox Private Limited; HR Intern (Recruitment), SocioBlend
- **Skills** – professional skills and languages

## CSS highlights
- Flexbox navigation bar, sticky at the top; on phones the links become a sideways-scrolling row
- Each section is a two-column grid: the heading sits in a sticky left rail, content on the right
- Responsive cards: the experience cards use a container query to switch between stacked and two-column layouts
- One palette defined as custom properties: navy ink from the printed resume, cool paper, and safety orange used only for current roles and interaction
- Type: Archivo (variable width axis) for headings and labels, Source Serif 4 for reading text, fluid sizes with `clamp()`
- Element, class and ID selectors, each group labelled in `style.css`
- Print stylesheet, so the page prints as a clean paper CV; reduced-motion support
