# Save the Date — Yuki & Blez

An animated, self-contained Save the Date for two software engineers.

Open `index.html` in any modern browser. It "deploys the wedding" as a tasteful
charcoal-on-cream build log that streams by, draws the emerald calla lily as the
final build artifact (a `[████] %` counter, the line revealing left-to-right),
then settles into an elegant Cormorant card.

**April 18, 2027 · Cebu, Philippines**

## Notes
- One HTML file. Cormorant + JetBrains Mono via Google Fonts (system fallbacks).
- Animated WebGL background (flowing emerald ink on paper) via three.js loaded from a CDN. If the CDN/WebGL is unavailable (e.g. offline), it degrades gracefully to a plain cream background — everything else still works.
- Responsive: fills the phone screen edge-to-edge on portrait phones; floats as a framed paper on larger screens.
- `index.html?formal` skips the animation and shows the static card (handy for sharing the "production" frame). `prefers-reduced-motion` is honored.
- Engineer easter eggs: open DevTools for a `git log` love-note; type `git`; hover the lily; click/tap to replay.
- `assets/original.jpg` is the original printed design; `assets/lily.png` is the emerald calla lily line extracted from it (so the drawn flower matches the design exactly).
