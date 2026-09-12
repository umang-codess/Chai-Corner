# umang Chai Corner

A small interactive order board built while learning Tailwind CSS. Single HTML file, no build tools, no dependencies to install.

## Overview

umang Chai Corner is a fictional tea stall's order board. It lists a small chai menu, lets you tap `+` / `−` to build an order, and keeps a running bill total — all styled with Tailwind CSS and driven by a small amount of vanilla JavaScript.

## Features

- Live order counter per menu item
- Auto-calculated total (item count and amount)
- One-click reset
- Highlighted "special of the day" item
- Fully responsive, no external JS libraries

## Tech stack

| Layer      | Tool                         |
|------------|-------------------------------|
| Markup     | HTML5                         |
| Styling    | Tailwind CSS (CDN build)      |
| Behavior   | Vanilla JavaScript             |
| Typography | Google Fonts — Baloo 2, Inter |

## Getting started

No terminal or build step required.

1. Download `index.html`
2. Open it directly in any browser (double-click, or drag it into a browser window)

That's it — Tailwind is pulled in via CDN at runtime, so there is nothing to install.

**Optional:** for auto-reload while editing, open the folder in VS Code and run it with the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.

## Project structure

```
.
├── index.html      # the project — a single self-contained file
├── notes.txt   # not uploaded, bcoz personal notes on Tailwind used in this project 
└── README.md
```

## Why this project

Built as a hands-on exercise while learning Tailwind CSS  utility-class styling, a custom theme (colors, fonts) via `tailwind.config`, and basic state-driven interactivity, without reaching for a generic todo-list or portfolio template.

## License

Free to use, modify, and learn from.

## Author

Built by Umang Dubey.
