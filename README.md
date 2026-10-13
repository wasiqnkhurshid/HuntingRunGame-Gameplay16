# Hunting Run — Gameplay16 Precision Shooting Lab

[Play in a browser](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay16/). No installation or login required. Choose **SHOOTING LAB**, then **A: PRECISION TAP** or **B: HOLD / RELEASE**, then **START / RESTART TEST**.

A: tap Shoot to release an arrow. B: hold briefly to steady, then release. Both use fast, shallow physical arrows with narrow release-only prediction and actual obstacle blocking. Move into the correct lane and choose a useful distance/posture. Neither a long hold nor an eligible target guarantees a hit. There is no meter or targeting minigame. One tap/release fires once; holds never auto-fire. Swiping on or across Shoot moves; B swipes cancel without spending arrows. Independent fingers can move and shoot. Keyboard: A/D or arrows, W/Space, S, Enter (hold/release for B), Escape. Mouse supported.

Defaults: speed 140 m/s, gravity 0.6 m/s², assistance control 60%, 0.025 m collision expansion, base range 40 m, Accuracy 50, Range 40, cooldown 0.65 s, steadying base 350 ms. Cone at Accuracy 50 is about 1.80°. Actual correction is only a fraction of the desired angle and decreases at far distance. Long holds lose assistance after 900 ms. Controls allow comparison of assistance, tolerance, velocity, range, cooldown and steadying duration. Range does not improve aiming accuracy.

Normal seeded 90-second Jungle, 32 m/s, Closer camera, 99 starting arrows, ordinary health/obstacles/pickups/natural animals. Pause → SHOOTING LAB → START restarts the chosen seed; RESET LAB restores defaults. Existing movement rules remain 18 dp, Shoot 84 dp. Low monkeys at extremely close range can require ducking; high birds can require jumping or earlier timing.

Source `4c374cb16621dcb88601c308893226704576b4f0` on `codex/gameplay16-precision-shooting`. Compiled WebGL only. Saves isolated through `HuntingRun.Gameplay16:/idbfs` and a separate save key/file. Gameplay12–15 sources/sites remain unchanged.

Unity and Chrome desktop/mobile-viewport touch simulation passed, including 30/60/120 FPS fixtures and independent fingers. Physical Android/iPhone, Safari, human difficulty/rhythm and sustained mobile performance remain untested. WebGL2/WebAssembly required; download, storage and startup vary by browser/device.

## Rollback

Unpublish only this repository's Pages to withdraw Gameplay16. After future updates, restore tag `gameplay16-precision-shooting` into a **new main commit** and push; do not force-push. Earlier sites remain independently available: [Gameplay12](https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/), [Gameplay13](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay13/), [Gameplay14](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay14/), [Gameplay15](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay15/).
