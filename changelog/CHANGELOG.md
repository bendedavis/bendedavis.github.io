# bendavis.io - full change log

Newest first. Every change to the site gets an entry here.

## 1.3.1 - 2026-11-06
- CODER landing page removed (Ben's call - "only link to the
  manual"): the manual's home is the direct link,
  /coder/manual.pdf. The /coder/ page is gone; the PDF and
  the front page are unchanged.

## 1.3.0 - 2026-11-06
- CODER manual published on the site: the complete manual for
  the CODER live-coding module now lives at /coder/manual.pdf,
  with a small landing page at /coder/ (the store page cannot
  host documents, so the manual's home is here). Front page
  unchanged.

## 1.2.1 - 2026-11-05
- Test page REBUILT to Ben's corrected brief: a professional
  company page from the 90s, not a personal blog. Masthead with
  the panel-font wordmark and a ruled navigation bar, company
  voice throughout (products, catalog-style module listing,
  company background), copyright footer. The personal-blog
  material and jokes are out. Style v4: Arial, lighter body
  text. The live style backend is unchanged.

## 1.2.0 - 2026-11-05
- The /test page is now DYNAMIC (Ben's architecture: static
  frontend, dynamic backend). The page itself is static HTML on
  GitHub Pages, but it polls a live style state (held in repo
  issue #1, of all places) every 3 seconds and re-renders -
  colors, font, layout, headline treatment - so the style can be
  steered live with hotter/colder feedback while Ben watches.
  When a style wins, it gets baked into the static pages.

## 1.1.6 - 2026-11-05
- COMING SOON re-rendered per Ben's exact spec: the SAME
  letterforms and size as the original red render (kit font,
  filled geometry) - now white and hollow, the letterforms'
  silhouette outline only, no cell grid.

## 1.1.5 - 2026-11-05
- COMING SOON: the Argon contour lettering is out (Ben's call -
  "original was better"). Restored the panel kit-font white
  outline render from 1.1.2.

## 1.1.4 - 2026-11-05
- COMING SOON outline redesigned by Argon per Ben; white outline
  only. The hollow-square render is replaced by Argon's engraved
  double-rule lettering: a 1 px pure-white outer contour with a
  1 px steel-gray inner calibration rule, hollow throughout,
  392x64 (cap height exactly two-thirds of the logo's).

## 1.1.3 - 2026-11-05
- Front page vertical centering made real (full-height page +
  middle-aligned cell); the logo and COMING SOON now sit at the
  true center of the window, both ways.

## 1.1.2 - 2026-11-05
- COMING SOON re-rendered per Ben: no red - the letters are now
  hollow outlines in white (panel-font glyphs drawn as outlines).

## 1.1.1 - 2026-11-05
- Coming-soon page stripped to the essentials per Ben: logo and
  COMING SOON only, centered both ways. Store link, explanatory
  text and the test-site pointer removed from the front page
  (the test site itself is unchanged at /test).

## 1.1.0 - 2026-11-05
- Main page is now a "coming soon" placeholder: black page, the
  name and COMING SOON set in the Voltage Modular panel bitmap
  font (the 3x5 glyph set from the module design kit, rendered
  to PNG), a store link, and a pointer to the test site.
- The full site (frameset + all four pages) moved to /test for
  testing while the real front page is designed.

## 1.0.0 - 2026-11-05
- Site launch. Hand-written HTML 4.01 frameset: left navigation
  frame + content frame, black background, Times New Roman,
  no CSS, no scripts, no tracking.
- Pages: Home/Blog (main.html), Modules (modules.html),
  Music (music.html), About (about.html).
- Modules page lists the live Series One catalog and bundles;
  Music page lists Cycles (2019), Mures EP (2024), Verified
  (2025), Verified (DJ Manny Remix) (2026).
- Hosted on GitHub Pages (repo: bendedavis/bendedavis.github.io)
  with the custom domain bendavis.io (Namecheap DNS, HTTPS via
  GitHub's certificate).
