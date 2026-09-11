# Portfolio Project Context & Architecture Notes

## About the Developer
- **Developer:** 15-year-old student at Genta Saraswati learning frontend development.
- **Workflow:** Architect & Construction Worker model (Developer designs the structure and makes architectural decisions; AI assists with syntax and implementation).

## Project Structure & Files
1. `home.html` - Home page.
2. `contacs.html` - Contact page with custom underline inputs, left border container, and social/contact info blocks. Styled via `portfolio.css`.
3. `about.html` - Newly restructured About Me page featuring:
   - `.aboutme` (Master 2-column flex parent container).
   - `.aboutme-text` (Left side holding headings, bio paragraphs, and the 3-column info footer).
   - `.aboutme-info` / `.info-col` (3-column footer holding Education, Dev Stack, and Featured On).
   - `.aboutme-img` (Right side holding the upcoming tilted photo stack).
4. `portfolio.css` - Global stylesheet with imported Google Fonts and section-commented styles.

## Next Steps / Up Next
- Write CSS rules for `.aboutme` layout (Flexbox/Grid layout for left text and right image).
- Style `.aboutme-info` and `.info-col` for the 3-column footer.
- Build the CSS tilted photo stack effect for `.aboutme-img`.
