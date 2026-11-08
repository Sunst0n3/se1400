# Milestone 6 - Final Project Mobile Implementation

Due: Tue Nov 10, 11:59 PM (Canvas). Worth 1 point in the Final Project group.
Late work loses about 1% per day (matches how M3 and past labs were docked).

This folder is a straight copy of `milestone5` (Task 1, step 1 of the assignment).
Nothing in the HTML or CSS has been changed yet. The mobile work is yours to write:
the syllabus says code from tutorials or AI counts as cheating, and every
submission goes through AI detection.

## What Canvas asks for
- [x] Folder called `milestone6`, copied from `milestone5`
- [x] Meta viewport tag (already in `index.html` from M5, keep it)
- [ ] Two media queries in `style.css`: one for viewports under 992px, one for 768px and below
- [ ] At 992px: the center column of the grid is 768px wide
- [ ] At 768px: the center column is 100% wide (you will likely need to turn off the left and right columns)
- [ ] Keep the M5 grid code `minmax(0px, 1fr) repeat(6, minmax(0, 175px)) minmax(0px, 1fr)` as the base layout
- [ ] Responsive images and background images (try `<picture>` instead of hiding images on small screens)
- [ ] Flexbox for the menu and image galleries, adjusted for each size
- [ ] Validate HTML and CSS as you go
- [ ] Push to GitHub, then submit the GitHub Pages link to Canvas:
      https://sunst0n3.github.io/se1400/milestone6/index.html

## Carry-over from earlier feedback
- Brayden on M4: use one grid on `body` (or one wrapper div) and put all content in that single grid, not several grids.
- He offered to help during lab time.

## Things in this site to check at small sizes
- `.hero` uses `images/hero.svg` as a background image
- Box images: `games.jpg`, `relax.jpg`, `spend.jpg`
- Header: logo + nav (good place for flexbox wrap)
- Footer: left and right blocks

## Next milestone (heads-up)
Milestone 7 (Content Creation and Final Presentation) is due Dec 3 and is worth 100 points,
almost all of the Final Project grade. It builds on this folder: subpages averaging about
300 words each, your own or licensed images, an 8 to 12 minute presentation, a zip of
the site, and removing the `noindex, nofollow` robots tag before publishing.
