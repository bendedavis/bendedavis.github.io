# bendavis.io - full change log

Newest first. Every change to the site gets an entry here.

## 1.7.2 - 2026-11-07
- CODER manual (/coder/manual.pdf) revised per Ben's ruling:
  the language reference is now complete. All 38 words of the
  CODER language have full entries (argument ranges and exact
  behaviour), plus the gate() rule, pattern reading rules,
  feedback rules, and the full list of edit-time checks -
  extracted from the build-10 implementation, not the old
  manual. Two corrections: the error readout is the status
  line at the top of the panel (not under the PLAY box), and
  quantize tie-breaking is stated per mode. 7 pages -> 14.
  Manual source: ~/workspace/vm/coder-rescue/manual.md;
  gap report: ~/workspace/coder-manual/GAP-REPORT.md.
  Published to the live site 2026-11-07 on Ben's GO.

## 1.7.1 - 2026-11-07
- /test REMOVED from the public site. With the site live at
  the root, /test was a second public copy of every page.
  Changes are now built on a staging branch and previewed
  privately before publishing; the front page changes only
  on Ben's GO. The pages themselves are unchanged at the
  root, and the /test files stay in the repo history.

## 1.7.0 - 2026-11-07
- THE SITE IS LIVE: the /test site is promoted to the front
  page of bendavis.io, per Ben's ruling (2026-11-07 09:27 -
  the promotion waited only on the finished case render,
  approved 2026-11-07 10:29). The root now serves the full
  site: home, the Voltage Modular catalog, and the Tern page.
  The coming-soon page is retired; headline.png and soon.png
  stay in the repo as its record. /test stays up, unchanged
  apart from the case tile below.
- Home: the Voltage Modular tile image is now CASE2 - the
  two-tier case holding the top ten modules (top row KICK,
  BOOL, RECT, QDIV, BELL at ~45 degrees; bottom row BONG,
  FOLD, ORBIT, PLATE, TIC at ~20 degrees), composited from
  the modules' own flat front panels - no generated pixels.
  Case design by Argon (HIGH consult), adjudicated against
  the real masters and built by Muse; approved by Ben.
  On-page image renders/CASE2.png; the full 2400x1800 master
  is renders/CASE2-2400.png. This closes the 1.5.1 interim:
  the CASE.png attempt (1.5.0) and the SKIFF.png skiff stay
  in the repo as the documented earlier attempts.

## 1.6.2 - 2026-11-06
- /test Tern page: the macOS build is out - the greyed COMING SOON
  tile is now a live download button for Tern-0.3.0-beta.1.dmg
  (universal VST3 + standalone). Beta line updated: all three
  platforms available; the Mac build runs to about November 20,
  2026, a day past the Windows/Linux builds.

## 1.6.1 - 2026-11-06
- REVERT of 1.6.0 at Ben's direction: the landing page is back to
  the plain coming-soon page. The support@ + header-logo change
  belongs on the Cherry Audio store page, not bendavis.io.

## 1.6.0 - 2026-11-06
- Landing page rebuilt in the test site's Style C treatment: the
  headline logo now sits as a page header (same logo and header
  styling as /test), COMING SOON below it.
- Public support contact added: support@bendavis.io (mailto),
  shown on the landing page.

## 1.5.1 - 2026-11-06
- /test home: INTERIM REVERT - the Voltage Modular tile image
  is back to the flat 19-module skiff (renders/SKIFF.png).
  The two-row virtual case (renders/CASE.png, shipped in
  1.5.0) failed Ben's review as a warped composite and is
  SUPERSEDED, pending an Argon-designed case rebuild.
  CASE.png stays in the repo and on disk as the documented
  failed attempt; it is not deleted.

## 1.5.0 - 2026-11-06
- /test home: the Voltage Modular tile image is now a two-row
  virtual case (renders/CASE.png): the top 10 modules, 5 + 5 -
  top row KICK, BOOL, RECT, QDIV, BELL tilted back ~45 degrees;
  bottom row BONG, FOLD, ORBIT, PLATE, TIC at ~10 degrees -
  with blank panels padding each row. Membership and order are
  Ben's pick, revisited as sales data lands. The full
  19-module skiff (renders/SKIFF.png) is unchanged and remains
  the complete-catalog image wherever it is referenced,
  including its regenerate-on-approval rule.

## 1.4.0 - 2026-11-06
- /test Tern page copy rewritten as product copy: the bullets
  now describe Tern as the instrument it is (a step sequencer,
  sampler and FX instrument in one grid) instead of reading
  like a beta test report. The beta facts sit in one
  small-print line: public beta 0.3.0, Windows and Linux
  available now, macOS in development, this beta build runs
  until about November 19, 2026.
- /test home: the Voltage Modular tile image is now a full
  skiff render (renders/SKIFF.png) - every approved module
  loaded side by side in gallery order, blank panels filling
  the last row. STANDING RULE: the skiff is regenerated every
  time Cherry Audio approves a module; the new module's
  render joins the skiff at approval.

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
