# Our Little Forever
A mobile-first birthday universe for Baby Cakes. No build step, account, API key, or paid service required.

## Open it
Open index.html in a modern browser. For hosting, upload the CONTENTS of  to any static host (GitHub Pages, Netlify, Cloudflare Pages, or your own web server). index.html must be at the root of the published folder. Keep the three other files beside it. The included .openai folder is hosting metadata for the companion Sites deployment; other hosts do not need it.

## Make it yours
Edit content.js in a text editor. Keep quotes, commas, brackets, and the window.CONTENT assignment intact. Escape apostrophes with a backslash, or use double quotes around that text.

- name: her nickname. initials: replace YOU + BC with your actual initials.
- compliments, notes, and reasons: replace the sample messages with your own. Keep exactly 100 reasons for the 100-card collection.
- quiz: replace the sample relationship questions and answer options. correct is a ZERO-based answer index (0 means the first answer).
- rewards: six romantic rewards; keep six so they match the wheel's six slices. The text result identifies the winning reward.
- surprise: your real birthday surprise. It is in the website source and is a playful reveal, not a secure secret.
- recap: title/copy pairs for the playlist-inspired recap. These are editorial slides, not real Spotify listening data.
- synopsis and scene: your real love-story description and opening scene. The movie section is a story reading, not a generated video.
- photos.before / photos.after: relative image paths, for example assets/then.jpg and assets/now.jpg. Add those images inside assets/. Use matching portrait/landscape crops for best results.
- voices: title and src pairs. Add MP3 recordings inside assets/, then set src to assets/birthday-message.mp3. Empty src values show upload placeholders. The upload control previews files only in the current visit; it does not publish or permanently store them. Browser playback controls provide play, pause, seek, and volume.
- scrapbook: each page has title, caption, date, image, and symbol. Set image to a relative asset path or leave it empty for the illustrated placeholder. Add or remove pages as needed.

There are intentionally no invented relationship dates, private photos, or real recordings. Sample quiz questions and scrapbook memories are labeled. Replace these and the surprise before gifting. Text inside content.js is inserted safely as text; do not put HTML markup in the content fields.

## Appearance
The exact theme colors are CSS variables at the beginning of style.css: #22172E, #68446C, #D8A6BE, and #F7E7F0. The design uses system fonts and CSS illustrations with no external fonts, images, trackers, or network dependencies. Navigation groups all 14 experiences into four chapters. Layouts stack on small screens; the 100-card collection changes from ten columns to five. Reduced-motion preferences disable animation and smooth scrolling.

## What works
1. Five compliment flowers reveal individual messages.
2. One hundred unique heart cards can be collected, filtered, and drawn at random.
3. The relationship quiz scores answers and can be replayed.
4. The animated wheel chooses one of six rewards and prevents overlapping spins.
5. The scratch card works with touch/mouse/pen; a Reveal button is the keyboard-accessible alternative.
6. Love Wrapped has previous/next slides.
7. Our Love Story opens an editable opening scene.
8. Voice players accept permanent recording paths and local upload previews.
9. A range slider reveals the before and after photos.
10. Birthday wishes can be added, removed, and exported to a text file.
11. A star constellation displays your personalized initials.
12. The love-note jar draws a random note.
13. Catch the Hearts runs a 20-second game with touch/click and Space-key controls.
14. The scrapbook has animated page changes and previous/next controls.

## Storage and sharing
Collected hearts and wishes use localStorage on the current browser/device and site address. They do not sync or send messages to the birthday giver. Export wishes to keep a copy. Reset removes these saved hearts and wishes after confirmation. When browser storage is disabled, the site remains usable for the current visit. Upload previews are temporary; publish your media files and edit their paths to make them available on another device.

A static public deployment makes its files readable to visitors. Use your host's access settings if you want private sharing. The companion Sites deployment starts owner-private; it is not automatically accessible to Baby Cakes.

## Verification
JavaScript syntax and structural/content checks passed. An automated interactive browser preview was attempted but the preview tool timed out, so touch behavior, visual layout, audio playback, and full game interactions still need a final check in your own browser before gifting. Test once at a narrow phone width and once on desktop, then substitute your real content and check media paths.
