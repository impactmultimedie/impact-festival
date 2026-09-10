# Team workflow

## Suggested ownership

- Layout and shared styles: `src/layouts/Layout.astro`
- Navigation and footer: `src/components/Header.astro`, `src/components/Footer.astro`
- Homepage and hero: `src/pages/index.astro`, `src/components/Hero.astro`
- Program: `src/pages/program.astro`, `src/components/ProgramCard.astro`
- About and content: `src/pages/om.astro`
- Newsletter and accessibility testing: `src/components/Newsletter.astro`

Replace these roles with the actual team members after agreeing on ownership.

## Branch workflow

1. Pull `main` and create a focused branch, for example `feature/program-card`.
2. Implement and test the component with `npm run build`.
3. Push the branch and open a pull request.
4. Ask another team member to review and test locally.
5. Merge only after the build passes, then everyone pulls the updated `main`.

## Setup

```sh
git clone https://github.com/impactmultimedie/impact-festival.git
cd impact-festival
npm install
npm run dev
```
