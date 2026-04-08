# Polina's Site

Portfolio website built with Astro and component-based UI blocks.

The project includes:
- A main portfolio page at `/`
- A compatibility redirect at `/site` (redirects to `/`)
- Reusable portfolio components in `src/components/portfolio`
- External product/demo components in `src/components/external`
- Static assets in `public/assets`

## Tech Stack
- Astro
- React
- MUI (`@mui/material`, `@mui/icons-material`)

## Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Configure environment variables
Create `.env.local` (or copy from `.env.example`) and set values like:
```env
PUBLIC_SITE_TITLE=Polina Portfolio
PUBLIC_SITE_ROLE=Product Designer
```

### 3. Start development server
```bash
npm run dev
```

By default, Astro will run on `http://localhost:4321`.

## Scripts
- `npm run dev` - start local dev server
- `npm run build` - build production files into `dist/`
- `npm run preview` - preview production build locally
- `npm run astro` - run Astro CLI
- `npm run mcp:chrome` - run Chrome DevTools MCP tool

## Project Structure
```text
src/
  components/
    portfolio/   # portfolio design system components
    external/    # external product/demo components
  pages/
    index.astro  # main portfolio page
    site.astro   # compatibility redirect to /
public/
  assets/        # images, icons, source files
```

## Build for Production
```bash
npm run build
npm run preview
```
