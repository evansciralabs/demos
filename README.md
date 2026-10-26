# demos
A circuit-bent DTMF glitch-tone instrument in a single HTML file. No installs, no network, no telemetry — just open it and play. Free to use (MIT).
# GLØTCH_DIΛL · Evanscira Labs Demos

A demos repo for Evanscira Labs web experiments. First up: **GLØTCH_DIΛL** —
a circuit-bent, DTMF-inspired glitch tone generator. One HTML file, zero
dependencies, zero network requests (the CSP lock in the file refuses
everything). Open it and play. ⌁

## ▶ Play it
1. Download `glitch_dial.html`
2. Open it in any modern browser (desktop or phone)
3. Tap ⏻ to power up, then mash the keypad. That's it — button-mashing is the instrument.

## What's inside
- **12-key DTMF pad** — the human telephone matrix, each key showing its Hz
- **8 xenotype orbit buttons** — DRONE · PULSE · FRACTURE · GRAVITY · STUTTER · MIRROR · PHANTOM · CLOAK, spiraling around the pad and bending the sound while they orbit
- **Radar scope** — a vector-field HUD: drag points for stereo, amp, reverb, pitch; PHANTOM flips it to a reverse-delay sweep
- **4 tone engines** — DTMF · FM · NOISE · WARP
- **6 bend modes** — CLEAN · DRIVE · GLITCH · FULL · ECHO · VACUUM
- **Alien tunings** — leave the human ITU table for ALIEN-01 or your own CUSTOM bank
- **16-step sequencer** — steps, swing, gate, BPM; slide LEN to shorten the loop while it runs (the galaxy behind the face follows)
- **8 sample slots** — record your own takes from the output, or render a pattern into a slot
- **EXPORT** — take your patterns with you

Built as an SRC-D module: it runs standalone *and* drops into an ØMNI_FRΛMΞ rack as a face — but it never needs one.

## Privacy
Everything runs locally in the browser. The file's own Content-Security-Policy blocks all outbound connections, so it physically cannot phone home.

## License
MIT — free to use, modify, and redistribute. See .
