# RAPOY — Creative Developer Portfolio

Personal portfolio for Rafa Adi Prabowo, adapted from the supplied original React design source. The implementation preserves the source layout, section order, visual system, typography, spacing, and interaction patterns while replacing the previous identity and content with RAPOY's information and supplied assets.

## Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- lucide-react
- CSS animations and Intersection Observer based scroll interactions

## Run locally

1. Install dependencies:
   `npm install`
2. Start the development server:
   `npm run dev`
3. Create a production build:
   `npm run build`

## Supplied assets

Original user-provided portraits and project screenshots are stored in `public/assets/`. No third-party stock portrait or invented project screenshot is used.

## Contact

- Email: rafarapoy813@gmail.com
- GitHub: https://github.com/rapfoyyy
- Instagram: https://www.instagram.com/bowo.html1?rpxt=OG5sbTllcnh4a3Ri


## Revision notes

- The top infinite marquee now contains only original project screenshots; personal portraits are excluded from that strip.
- Marquee and project-gallery screenshots use `object-contain` so the original project captures remain fully visible.
- VALAUERA opens on the supplied “Ruang hidup, bernapas” homepage capture and includes a three-image manual gallery.
- KIYO ROW includes a two-image manual gallery; RAPOY AI SYSTEM uses its supplied original screenshot.
- Project galleries support previous/next controls, slide indicators, and mobile swipe gestures.
- “Beyond the Screen” autoplay runs while its section is visible, pauses only while the moving cards themselves are hovered, and filters transition events to the track animation.
- Development Focus and Creative Interests card groups, plus the Education group, use a centered max-width container so they align with the page axis on desktop and mobile.
- Education includes Primary School, Junior High School, Vocational High School, and a clearly marked Coming Soon entry for Bandung Institute of Technology (ITB) — Informatics Engineering.

## Validation status

All TypeScript/TSX source files passed a local TypeScript transpilation/syntax check, and all referenced local image assets were verified to exist. A full Vite production build was not run because dependency installation timed out in the execution environment. After extracting the project, run `npm install` and then `npm run build` to perform the production build locally.
