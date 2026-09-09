THE GRID — CREATIVE RACE V3

This version fixes navigation and rebuilds the transitions around a premium page-pull concept.

- Buttons now route and render correctly.
- The car/wheel transition has no background.
- The current page physically gets pulled off-screen with the car/wheel.
- The next page slides in underneath.
- Car motion is slower, smoother and heavier.
- Wheel transition is intentionally much larger.
- Main pages stay red/white/black.
- Team pages retain team-specific colors.
- More playful hover, press, HUD and menu behavior.
- One responsive build for desktop, tablet, iPhone and Android.

The private v4+ Universal master remains untouched.

V4 ROUTER FIX
The v4+ base is function-routed, not hash-routed. The creative transition now calls the
real page function at the midpoint of the car/wheel pull. This fixes the issue where
the animation played but the destination never appeared.
