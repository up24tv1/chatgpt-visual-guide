# Visual Guide to ChatGPT – Beginner's Companion (2025)

This repository contains a lightweight, **static site** that introduces new users to ChatGPT. It blends clear explanations with helpful tips, modern animations and sleek visuals to create an engaging experience. The guide is organised into five sections: Getting Started, Prompting, Advanced Features, Practical Use Cases and Best Practices. Each section contains a set of concise tips with icons and colour‑coded styling.

## Features

- **Dark, accessible theme** built with Tailwind CSS and the Inter font.
- **Responsive layout** that adapts from mobile to desktop screens.
- **Animated scroll effects** via the AOS library to gently guide the reader’s attention.
- **Icon‑driven cards** summarising the most important tips for each topic.
- **High‑resolution header images** generated using DALL·E for each section, ensuring a cohesive aesthetic without relying on external stock photography.
- **External resources** linking to OpenAI’s official documentation and release notes so that learners can verify facts and explore further.

## Usage

1. Clone or download this repository to your machine.
2. Open `index.html` in a modern browser – no build step or server is required.

To customise or extend the tips, edit the `tipsData` object in the `<script>` tag at the bottom of `index.html`. Icons and colours are defined by the `categoryIcons` and `categoryColors` maps.

## Hosting on GitHub Pages

If you’d like to publish this site online via GitHub Pages:

1. Create a new repository on GitHub named something like `chatgpt-guide`.
2. Commit all files from the `chatgpt_guide_site` directory to the repository root.
3. Push your changes to GitHub.
4. In your repository settings, enable GitHub Pages and select the `main` branch and `/ (root)` folder as the source.
5. GitHub will build and serve your site at `https://<your-username>.github.io/chatgpt-guide/`.

For more detailed instructions see the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages).

## Sources and attribution

The content of this guide is distilled from publicly available information about ChatGPT. For the most up‑to‑date details about new features, plans and release timelines, please consult OpenAI’s official resources such as the [ChatGPT release notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)【475733806838524†L25-L43】, the [ChatGPT overview page](https://chatgpt.com/overview/)【20559896282763†L256-L303】 and the [“ChatGPT can now see, hear and speak” blog post](https://openai.com/index/chatgpt-can-now-see-hear-and-speak/)【906759441861202†L125-L174】. Always verify critical information and usage policies directly from trusted sources.
