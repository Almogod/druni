# Happy Birthday 💝

A single-file interactive birthday surprise: `index.html` (Three.js + canvas-confetti from CDN, no build step).

**Flow:** Envelope → Memory Lane (3 Polaroids) → "Will you celebrate with me?" (runaway NO button) → confetti + letter.

## Customise
- **Name:** change `BIRTHDAY_NAME` at the top of the `<script type="module">` in `index.html`.
- **Photos:** look for `<!-- PHOTO_1 -->`, `<!-- PHOTO_2 -->`, `<!-- PHOTO_3 -->` and change each `src` (and `object-position` to adjust framing). Images live in `photos/`.
- **Captions / letter text:** edit them inline in `index.html`.

## Run locally
Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
```
