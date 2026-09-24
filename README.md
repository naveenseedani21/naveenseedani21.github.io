# Naveen Seedani — Portfolio

React + Vite portfolio featuring adapted React Bits MagicBento, ProfileCard, and Carousel components, a responsive connected skill tree, and six projects and four roles.

## Develop

- `npm ci`
- `npm run dev`
- `npm run build` produces static files in `dist/`.

## Update content

Edit project, experience, and skill data in `src/main.jsx`; update the theme and responsive layout in `src/style.css`. Replace the photo and resume in `public/` while retaining their filenames.

The supplied 2026 Austin resume is the primary source for employment details. WibeCheck details come from the earlier supplied resumes. Project dates and GPA are omitted because the supplied resume variants differ. Campus Dwellers has a verified public repository link. Little Lies links to its hosted game; its source repository is private. Add further project links to their `url` fields when available.

Photo: supplied by Naveen. Company logos: supplied by Naveen. The resume is included unmodified.

## Components

React Bits components were sourced from https://github.com/DavidHDev/react-bits and adapted to the portfolio's content, single-frame layout, keyboard navigation, responsive sizing, and reduced-motion preferences. See REACT-BITS-LICENSE.md.

## Hosting

Published at https://naveenseedani21.github.io/ through GitHub Pages.

Every push to `main` triggers `.github/workflows/deploy.yml`, which installs the locked dependencies, builds the static Vite site, and deploys `dist/` to Pages. Pages must use **GitHub Actions** as its build source. The user-site address uses Vite's default `/` base path.

The original site history is preserved. Legacy contact and thank-you URLs redirect to the new contact section. Email actions open the visitor's email app.
