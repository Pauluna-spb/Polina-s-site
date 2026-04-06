# External Product Components

This folder is reserved for components coming from other products that should stay separated from the portfolio design system.

Guidelines:
- Do not import `src/styles/figma-typography.css` or `src/styles/figma-colors.css` here unless explicitly needed.
- Keep external styles component-local or create dedicated external style tokens in a separate file.
- Avoid mixing components from this folder into `src/components/portfolio/`.
