<p align="center">
  <img src="poster.svg" alt="Which balloon are you? — A personality journey through the clouds" width="100%">
</p>

<h1 align="center">🎈 Sky Traveler — Balloons &amp; Sky</h1>

<p align="center">
  <em>A whimsical, cinematic personality quiz set against a living, animated sky.</em><br>
  <strong>Take the quiz → <a href="https://navybluecheese.github.io/sky-traveler/">navybluecheese.github.io/sky-traveler</a></strong>
</p>

---

## ✨ About

**Sky Traveler** is a single-page personality quiz that reveals what kind of *sky traveler*
you are — represented by your very own hot-air balloon type and color. The whole experience
unfolds against a persistent, gently animated sky filled with drifting clouds, hot-air
balloons, paper planes, kites, glowing sky lanterns, and flocks of birds.

It's a storytelling journey, not just a form. Each of the twelve questions is a little visual
scenario, the sky slowly warms toward golden hour as you go, and the final reveal is a
cinematic moment — your balloon rises, the clouds part, confetti bursts, and your result is
written in warm, poetic language.

Think *Studio Ghibli sky scene* meets a *cozy modern personality quiz*.

## 🌤️ Features

- **A living sky** — 6+ parallax clouds, bobbing balloons, gliding paper planes, fluttering
  kites, rising sky lanterns, drifting birds, and twinkling stars — all hand-coded as inline
  SVG and animated with `requestAnimationFrame`.
- **Cinematic intro** — a short three-slide story sequence sets the scene before the quiz.
- **12 scenario questions** — floating glass cards that hang from a little balloon, with
  answers as scattered "tag-cloud" pills and playful hover micro-animations.
- **A mood-reactive sky** — the gradient subtly shifts color and temperature based on your
  answers (calm blues, adventurous golds, dreamy pinks).
- **A flight-path progress bar** — a tiny airplane glides along a dotted map arc as you advance.
- **A big reveal** — mist, a rising result balloon, parting clouds, canvas confetti, a
  typewriter title, trait tags, a "sky wisdom" line, and a pairing.
- **8 personality types** — each with a unique balloon design, palette, description, and traits:
  *The Dreamer, The Explorer, The Nurturer, The Architect, The Adventurer, The Sage, The
  Creator,* and *The Guardian*.
- **Share your result**, browse **all eight balloon types**, or **fly again**.
- **Fully responsive** and touch-friendly, with reduced motion and performance care
  (fewer floaters on mobile, animations pause when the tab is hidden).

## 🛠️ Built with

- **HTML, CSS, and vanilla JavaScript** — no frameworks, no build step.
- **All graphics generated from scratch** with inline SVG and CSS — no external image files.
- Typography: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) and
  [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts.

## 🚀 Run it locally

It's a single file — just open it in a browser:

```bash
# clone, then either open index.html directly...
open index.html

# ...or serve it locally
python -m http.server 8000
# then visit http://localhost:8000
```

## 📂 Structure

```
.
├── index.html    # the entire website (HTML + CSS + JS, all in one file)
├── poster.svg    # the promo poster shown above
└── README.md
```

---

<p align="center"><em>Made with clouds, code &amp; a little wonder. ☁︎</em></p>
