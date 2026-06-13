# FIFA Match Carousel Studio

## What this is
Production-ready static site for generating 5-slide Instagram carousels for the next FIFA World Cup match.

## Files
- `index.html`
- `styles.css`
- `app.js`
- `README.md`

## Use the API key
1. Select `WorldCupAPI key` in Match source.
2. Paste your key in the API field.
3. Click `Make carousel`.

The app sends the key as `?key=YOUR_KEY` when calling the fixtures endpoint.

## Run locally
Open `index.html` in a browser or use a local server like:
`python -m http.server`

## Deploy live
### Netlify
- Drag the folder into Netlify deploy, or connect GitHub.
- No build command required.

### Vercel
- Import the GitHub repo.
- Framework preset: Other.
- Build command: empty.
- Output directory: root folder with `index.html`.

## Notes
- Instagram export size: 1080 x 1350 px (4:5).
- Use prompt changes to adjust hook, CTA, tone, and stage.