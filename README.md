# 🐍 Snake Animation

Automated GitHub contribution snake animation, generated with GitHub Actions and published as an SVG.

## 👀 Preview

![Snake Animation](https://github.com/jkdevcode/snake_animation/raw/output/snake.svg)

## ✨ Features

- Fully automated SVG generation
- Scheduled updates every 12 hours
- Clean output published to the `output` branch
- Lightweight and easy to maintain

## 🛠️ Technologies

- [Platane/snk/svg-only@v3](https://github.com/Platane/snk)
- [crazy-max/ghaction-github-pages@v3.1.0](https://github.com/crazy-max/ghaction-github-pages)
- GitHub Actions
- SVG output

## ⚙️ How Its Works

1. GitHub Actions runs on a schedule, on push to `main`, or manually.
2. `Platane/snk/svg-only@v3` generates the snake animation as `snake.svg`.
3. `crazy-max/ghaction-github-pages@v3.1.0` publishes the file to the `output` branch.
4. The README embeds the SVG directly from that branch.

## 📚 What I Learned

- How to automate visual assets with GitHub Actions
- How to publish generated files through a dedicated branch
- How to keep a project README simple, useful, and polished

## 🎯 Motivation

This project serves as a compact portfolio piece showing how automation can turn GitHub contribution data into a clean visual identity.
