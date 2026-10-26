# Tony Chancellor

A responsive React frontend built with Vite. Uses the supplied local photographs and Facebook Reels destination.

## Run

`npm install` then `npm run dev`. Build for static hosting with `npm run build`; the output is in `dist`.

The food gallery supports category filters, a keyboard-accessible lightbox, and arrow-key navigation. The hero includes slideshow controls. Animations respect reduced-motion preferences.

The Reels section embeds seven supplied Facebook videos, with individual Facebook links as fallbacks and a link to Tony�s full feed. Playback depends on Facebook availability, video privacy, browser policies, and any Facebook sign-in requirements. No backend, storefront, or sign-up service is included.

Update the feed URL and gallery items in `src/main.jsx`. Visual styles are in `src/style.css`. Original supplied files are preserved in the project root; the website uses copies in `public/images`.
