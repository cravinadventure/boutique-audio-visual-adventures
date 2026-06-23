# Library Sessions

Landing page for **Cravin' Adventure Studios** — recorded audio-visual DJ sets in St. Petersburg, FL.

A single, self-contained static page (`index.html`, inline CSS + JS) telling the studio's story: capture a DJ's set as an audio-visual time capsule built around who they are, made to share and to deepen authentic human connection.

## Structure

- `index.html` — the entire page (markup, styles, script in one file)
- `mitch-headshot-facing-camera-studio.jpg` — founder photo used in the hero bio

## Page flow

Hero (mission + founder) → two examples (Nicholas Lombardo, an individual's set recorded and posted; Luca Immersive, a brand's world streamed live) → Your Experience (Custom Lighting · Custom Visuals · Recorded Set · Share) → submission (Tell us your story → Submit Story button).

The **Submit Story** button links out to a Google Form (set the `href` in `index.html`).

## Hosting

Served via GitHub Pages from the `main` branch root, and embedded full-page into the Squarespace site at cravinadventure.com.

## Local preview

```bash
python3 -m http.server 4178 --directory .
# http://localhost:4178
```
