# VAULTNOTES
New vault app


# Notes — Pitch-Black Minimalist Workspace

A distraction-free, pitch-black notes workspace built with zero external dependencies. Designed for speed, privacy, and aesthetic clarity.






---

## Highlights

- **Pitch-Black Aesthetics**: Engineered with true blacks (`#000000`) and deep zinc surfaces (`#09090b` / `#121214`) to eliminate visual noise and reduce OLED battery drain.
- **Biometric & PIN Lock**: Simulated optical in-screen fingerprint sensor with pulse wave animations, WebAuthn platform biometric authentication (Touch ID / Face ID), and 4-digit PIN fallback.
- **Synthesized Audio Haptics**: Native Web Audio API tone synthesis with zero external audio assets—dynamic oscillator ticks, two-tone harmonic unlock chords (587 Hz / 880 Hz), and error bursts.
- **Three Switchable Layouts**:
  - **Keep Grid**: Fluid masonry-style note cards with pinned sections.
  - **Clean List**: Dense, distraction-free stream view for rapid scanning.
  - **Apple Split**: Dual-pane editor with live title/body text binding and real-time word counter.
- **Privacy & Offline First**: Zero tracking, zero telemetry, and zero mandatory backend servers. All notes persist in your browser's local sandbox storage (`localStorage`).
- **Data Mobility**: Instant one-click individual Markdown (`.md`) export, full workspace JSON backups, and lossless JSON restores.
- **PWA Ready**: Add to home screen on iOS and Android for a full-screen, native-feeling mobile app experience.

---

## Quick Start (Deploy in 30 Seconds)

Because this project is a single standalone file, you can host it for free on GitHub Pages without any build steps or CLI tools:

1. Fork or clone this repository.
2. In your repository on GitHub, navigate to **Settings** > **Pages**.
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`
4. Click **Save**. Your notes app will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `⌘ + N` / `Ctrl + N` | Expand quick note composer |
| `Esc` | Clear search / close active modal |
| `0` – `9` | Enter passcode digits on lock screen |
| `Backspace` | Delete last passcode digit |
| `Enter` | Trigger biometric scan authentication |

---

## Tech Stack

- **Markup & Logic**: HTML5 + Vanilla ECMAScript (ES6+)
- **Styling**: Tailwind CSS (via CDN) + Inter & JetBrains Mono typography
- **Audio Engine**: Web Audio API (`AudioContext`, `OscillatorNode`, `GainNode`)
- **Storage**: Browser LocalStorage API

---

## License

[[https://img.shields.io/badge/▶_Open_Notes_App-Live_Web-white?style=for-the-badge&logoColor=black]](https://sizumaru21-collab.github.io/YOUR_REPO_NAME/)

> 🔗 **Live Web App**: [[https://sizumaru21-collab.github.io/YOUR_REPO_NAME/](https://sizumaru21-collab.github.io/VAULTNOTES/)]([https://sizumaru21-collab.github.io/YOUR_REPO_NAME/](https://sizumaru21-collab.github.io/VAULTNOTES/)

MIT © [sizumaru21-collab](https://www.google.com/search?q=https%3A%2F%2Fgithub.com%2Fsizumaru21-collab)
