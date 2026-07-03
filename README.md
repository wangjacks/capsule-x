<p align="center">
  <img src="public/logo.svg" alt="CapsuleX Logo" width="120">
</p>

<h1 align="center">CapsuleX</h1>

<p align="center">
  A minimal, modern blog theme for Astro with capsule floating navigation.
</p>

<p align="center">
  <a href="https://github.com/wangjacks/capsule-x">GitHub</a>
</p>

---

## Features

- 🎯 **Capsule Floating Navigation** — Glassmorphism nav bar with backdrop blur
- 🌗 **Tri-State Theme** — Auto (follow device) / Light / Dark
- ⚡ **Fast** — Static generation with Astro, zero client JS by default
- 🏷️ **Tag System** — Filter posts by tags
- 📱 **Responsive** — Mobile-first design

### Coming Soon

- 📝 MDX Support
- 🔍 Pagefind Search
- 📊 Mermaid Diagrams
- 📖 Reading progress bar & TOC
- ✨ Scroll animations

## Getting Started

> ⚠️ This theme is under active development. Not yet published to npm.

```bash
git clone https://github.com/wangjacks/capsule-x.git
cd capsule-x
npm install
npm run dev
```

## Project Structure

```
capsule-x/
├── src/
│   ├── components/       # UI components
│   ├── layouts/          # Page layouts
│   ├── content/
│   │   └── blog/         # Blog posts (Markdown)
│   ├── pages/            # Route pages
│   └── styles/           # Global CSS
├── public/               # Static assets
└── docs/                 # Project documentation
```

## Development

```bash
npm run dev       # Start dev server
npm run build     # Build for production
npm run preview   # Preview production build
```

## License

[Apache 2.0](LICENSE)
