# 🎵 Moodwave — Audio Visualizer

A mood-based music visualizer built with pure HTML, CSS, and JavaScript. No frameworks. No dependencies. Just vibes.

![Moodwave Preview](https://via.placeholder.com/800x400/080810/ff4fd8?text=Moodwave+Visualizer)

## ✨ Features

- **6 Mood Presets** — Euphoric, Melancholy, Rage, Dreamy, Focus, Chill
- **4 Visual Styles** — Bars, Wave, Circle, Particles
- **Live Controls** — Adjust speed and intensity in real-time
- **Dynamic Theming** — Colors, glow, and background shift per mood
- **Zero Dependencies** — Pure vanilla HTML/CSS/JS, no build step needed

## 🚀 Getting Started

Just open `index.html` in your browser. That's it.

```bash
git clone https://github.com/YOUR_USERNAME/moodwave.git
cd moodwave
open index.html
```

Or serve it locally:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## 🎨 How It Works

Moodwave simulates audio frequency data and renders it across four visual modes using the Canvas 2D API:

- **Bars** — Classic spectrum analyzer with mirrored bars
- **Wave** — Layered sine wave interference patterns
- **Circle** — Radial spectrum that rotates with the beat
- **Particles** — Physics-based particle system driven by frequency peaks

Each mood applies a unique color palette, BPM simulation rate, and glow intensity.

## 🗂 Project Structure

```
moodwave/
└── index.html   # Everything lives here — self-contained, single file
```

## 🛠 Customization

Edit the `MOODS` object in the `<script>` tag to add your own moods:

```js
const MOODS = {
  yourMood: {
    bg: '#0a0a0a',
    c1: '#ff0055',
    c2: '#ff9900',
    c3: '#ffff00',
    glow: 'rgba(255,0,85,0.4)',
    label: 'YOUR MOOD // 100 BPM'
  }
}
```

## 📄 License

MIT — do whatever you want with it.
