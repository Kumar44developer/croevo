# Croevo — Digital Coins

A polished, single-page 3D coin showcase built with pure HTML and CSS. Golden Bitcoin-style coins rotate in real 3D space with depth-accurate faces, soft glow lighting, and an interactive hover speed-up — no JavaScript, no build step, no dependencies.

## Features

- **True 3D rotation** — Coins spin on the Y axis using CSS `perspective` and `transform-style: preserve-3d` for realistic depth.
- **Two-sided coin faces** — Distinct front and back faces rendered with `backface-visibility` for a genuine flip effect.
- **Metallic gradient finish** — Layered gold gradients, inset highlights and edge borders recreate the look of a struck coin.
- **Ambient glow** — Soft radial glow and drop shadows give each coin presence against the dark backdrop.
- **Interactive hover** — Spinning accelerates when a coin is hovered for a responsive, tactile feel.
- **Responsive grid** — Auto-fitting layout scales cleanly from mobile to desktop.
- **Zero dependencies** — A single self-contained `index.html`. Nothing to install.

## Tech Stack

| Layer     | Technology                     |
| --------- | ------------------------------ |
| Markup    | HTML5                          |
| Styling   | CSS3 (3D transforms, gradients)|
| Animation | CSS `@keyframes`               |
| Fonts     | System font stack              |

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Kumar44developer/croevo.git
cd croevo
```

## Run Locally

Because the project is a single static file, any of these work:

Open `index.html` directly in a modern browser, or serve it with any static server:

```bash
python -m http.server 8099
```

Then visit `http://localhost:8099`.

## Project Structure

```
croevo/
└── index.html    # Markup, styles, and animations for the coin showcase
```

## Browser Support

Works in all modern evergreen browsers with CSS 3D transform support: Chrome, Edge, Firefox, and Safari.

## License

Released under the MIT License.
