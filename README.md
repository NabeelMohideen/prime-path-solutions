# Prime Path Solutions

Marketing site for Prime Path Solutions built with Next.js 15, React 19, TypeScript, and Tailwind CSS. The site includes a hero, service overviews, testimonials, FAQs, and dedicated service detail pages.

## Tech stack
- Next.js 15 (App Router) with TypeScript
- React 19
- Tailwind CSS for styling
- Framer Motion for animations
- Lenis for smooth scrolling
- ESLint for linting

## Getting started
1) Prerequisites: Node.js 18.18+ and npm.
2) Install dependencies:
	- `npm install`
3) Run the dev server (Turbopack enabled):
	- `npm run dev`
	- Visit http://localhost:3000
4) Production build:
	- `npm run build`
5) Start production server (after build):
	- `npm start`
6) Lint:
	- `npm run lint`

## Project structure (key paths)
- src/app/layout.tsx — global layout, fonts, header/footer, suspense fallback
- src/app/page.tsx — home page wiring for hero, introduction, services, testimonials, FAQs
- src/app/services/* — individual service pages
- src/components/* — shared UI components (hero, navbar, services grid, etc.)
- src/sections/* — content sections used across pages
- public/img/* — marketing assets and icons

## Notes
- Fonts: Geist and Poppins are loaded via next/font.
- Dev server uses `next dev --turbopack` by default; remove `--turbopack` if you prefer the classic dev server.