# The Character Oracle

An interactive character questionnaire for writers, directors, actors, and animators. Draw a tarot card, answer the question. 253 prompts across 16 categories help you discover who your character really is — not just what they do.

Built as a single, self-contained HTML file — no installation, no dependencies, no server required.

---

## What it does

- **253 questions** across 16 character categories — from identity and family to morality, intimacy, and the supernatural
- **Rider-Waite-Smith Tarot imagery** — each category is paired with a card from the public domain RWS deck
- **Random draw** — click Question Your Character for a random question from anywhere in the deck
- **Sequential navigation** — step through questions in order using Prev / Next
- **Section jump** — skip directly to any of the 16 categories
- **Typewriter reveal** — questions appear character by character for dramatic effect
- **Progress tracking** — a live counter and progress bar show where you are in the full deck
- Runs entirely in the browser — no data is collected or stored

---

## The 16 categories

| # | Category | Tarot Card |
|---|----------|------------|
| 1 | The Basics | The Magician |
| 2 | Family | The Empress |
| 3 | Friends & Others | The Star |
| 4 | Childhood | The Sun |
| 5 | Teen & Young Adult | The Chariot |
| 6 | Past Influences | Wheel of Fortune |
| 7 | Beliefs & Opinions | The High Priestess |
| 8 | Likes & Dislikes | Temperance |
| 9 | Self Image | The Hermit |
| 10 | Occupation & Finance | The Emperor |
| 11 | Drugs & Alcohol | The Devil |
| 12 | Sex & Intimacy | The Lovers |
| 13 | Morality | Justice |
| 14 | Supernatural | The Tower |
| 15 | Goals & Future | The World |
| 16 | Miscellaneous | The Fool |

---

## How to use

1. Open the live URL in a browser
2. Click **Click to Begin** on the title screen
3. Click **Question Your Character** to draw a random question
4. Use **Prev** / **Next** to step through questions in sequence
5. Use **◀◀** / **▶▶** to jump to the first or last question
6. Click the section title (e.g. *Character Traits: The Basics*) to jump to a specific category

### Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Space` or `Enter` | Draw a random question |
| `←` | Previous question |
| `→` | Next question |

---

## Embedding

### Squarespace / any website

Add a Code Block and paste the following, replacing the URL with your own GitHub Pages URL:

```html
<iframe
  src="https://YOUR_USERNAME.github.io/character-oracle/"
  width="100%"
  height="700px"
  frameborder="0"
  style="border: none;"
></iframe>
```

Adjust the `height` value to suit your layout. A minimum of `650px` is recommended for the full interface to display without scrolling.

### Miro

Add an **Embed** widget and paste the GitHub Pages URL. Works best as a facilitated screen during a writers' room or rehearsal session.

---

## Deploying to GitHub Pages

1. Rename `character-oracle.html` to `index.html`
2. Push to a new GitHub repository
3. Go to **Settings → Pages → Source**, set branch to `main` and folder to `/ (root)`
4. Save — your live URL will be `https://YOUR_USERNAME.github.io/character-oracle/`

Deployment takes approximately one minute.

### Updating the file

1. Go to your GitHub repository
2. Click `index.html`
3. Click the pencil ✏ icon to edit, or use **Add file → Upload files** to replace it
4. Commit — the live URL updates automatically within a minute or two

---

## Technical notes

- Tarot card images are loaded from [Wikimedia Commons](https://commons.wikimedia.org) and are in the public domain (Rider-Waite-Smith deck, first published 1909)
- No frameworks, no build tools, no dependencies — pure HTML, CSS, and vanilla JavaScript
- Fonts loaded from Google Fonts (Rajdhani + Barlow); requires an internet connection to render correctly
- No data is sent anywhere — all interaction is local to the browser

---

## Credits

Developed by [Curated Place](https://www.curatedplace.com) — Creative Professional Development.
