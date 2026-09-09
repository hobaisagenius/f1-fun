THE GRID — CREATIVE RACE V10 REFINEMENT

This pass intentionally refines rather than redesigns V9.

ADDED / IMPROVED
- Higher contrast for micro-labels including THE ARCHIVE.
- First-session-only F1 five-light opening sequence (~1.6s total).
- More physical page-pull treatment.
- Menu-specific racing motifs.
- Team-detail personality accents.
- Desktop driver-photo parallax and touch push-in.
- Optional Timing Mode experimental skin.
- Existing optional sound retained and refined in the HUD.
- Landscape phone, safe-area, touch, narrow-screen and reduced-motion fixes.
- Existing universal desktop/tablet/iPhone/Android behavior retained.

Sound remains OFF by default.
Timing Mode is intentionally hidden on narrow phones to keep the HUD uncluttered.

V10.1 PATCH
- Fixed Ferrari identity on the team grid and Ferrari detail page.
- Fixed driver photos appearing almost black; the images were loading but V10 styling obscured them.
- Preserved all V10 routing, transitions, sound, Timing Mode and universal responsive work.
- Added cache-busting for GitHub Pages.

V10.2 SCREENSHOT + CURRENT-GRID AUDIT
- Rechecked the screenshots supplied after V10.
- Improved Ferrari identity sizing and removed dependence on the generic shield presentation.
- Driver photography now renders at normal brightness with a bottom-only readability gradient.
- Long driver names are constrained so they cannot collide with card edges.
- Ferrari hero body copy and small metadata have stronger contrast.
- Added graceful visual fallbacks for future broken remote image URLs.
- Corrected current 2026 Red Bull/Racing Bulls driver pairing where stale records were found.
- Preserved V10's routing, Race Mode, Timing Mode, sound, transitions and universal responsive system.

V10.3 FERRARI LOGO PATCH
- Replaced the Ferrari wordmark with a Ferrari shield/badge image.
- Applied globally through the shared Ferrari logo mapping.
- Ferrari now uses shield proportions on the Teams grid and Ferrari detail page.
- Kept all V10.2 routing, animations, sound, Timing Mode, driver photo fixes and universal responsive behavior.

V10.4 FERRARI CREST CLEANUP
- Removed the artificial clip-path and border treatment that made Ferrari's badge look chunky/weird.
- Uses the actual shield image at natural proportions.
- Reduced crest size on cards and team hero so it feels integrated instead of oversized.
- Added multiply blending on Ferrari red to visually suppress the JPG background edge.
- Kept all V10.3 routing, driver-image, sound, Timing Mode, transition and universal fixes.

V10.5 CLEANEST V10
- Rebuilt Ferrari shield as a local transparent asset so the red plate/background is gone.
- Fixed Teams heading clipping beneath the fixed header.
- Re-proportioned team cards and car stages.
- Reworked driver cards so portrait framing starts at the top and names stay controlled.
- Compact 3-column Legends layout with no giant empty spaces.
- Standardized Archive card dimensions.
- Moved Race Mode HUD to bottom-right so it stops covering card copy.
- Cleaned team-detail option card proportions.
- Retained V10 animations, sound, Timing Mode, routing and universal phone/tablet support.

V10.6 BEST/CLEANEST FINAL
- Embedded Ferrari shield directly in app.js as a data URI: no assets-folder dependency.
- Tightened driver cards and enlarged/cropped portraits so faces and torsos are proportionate.
- Reduced long driver-name sizing and protected text against card-edge collisions.
- Rebalanced team cards, car placement, logos and names.
- Fixed fixed-header/title clipping with stronger page top spacing.
- Removed stray decorative/transition text from team-title stacking contexts.
- Tightened Legends and Archive card rhythm.
- Shrunk/moved Race Mode HUD so it cannot cover primary content.
- Preserved V10 navigation, transitions, sound, Timing Mode and universal responsiveness.
