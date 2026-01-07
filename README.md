# Baroque — Related Articles UI Component

Baroque is a refined front-end UI demo showcasing a **modern “Related Articles” website section**, designed with clarity, scalability, and visual hierarchy in mind. The project emphasizes component isolation, typographic precision, and responsive layout techniques suitable for production-grade web platforms.

This repository serves as a **design and implementation reference**, demonstrating how a simple content-driven component can be built cleanly using semantic HTML and modular CSS without relying on heavy frameworks.

## Preview
<img width="1920" height="868" alt="baroque" src="https://github.com/user-attachments/assets/35113259-667d-4b97-a91d-3390cb4cda8e" />



### Live Demonstration

[View Baroque](https://lefajmofokeng.github.io/Baroque)

---

## Project Overview

The Baroque component represents a **content discovery section** commonly found on editorial platforms, blogs, digital magazines, and corporate websites. Its structure and styling are intentionally framework-agnostic, allowing seamless adaptation into existing systems.

### Core Highlights

* Fully responsive grid-based layout
* Clean, semantic HTML structure
* CSS isolation via prefixed class naming (`ra-*`)
* Modern typography using Google Fonts
* CSS variables for scalable theming
* Image handling with consistent aspect ratios
* Minimal, maintainable codebase


## Technical Breakdown

### Structure

* **HTML5**

  * Semantic elements (`header`, `article`, `section`)
  * Accessibility-conscious markup
* **CSS3**

  * Custom properties (CSS variables)
  * Grid-based layout system
  * Component-scoped reset strategy
  * Mobile-first responsive breakpoints

### Design Philosophy

The component is designed with:

* **Isolation** – No global CSS leakage
* **Reusability** – Drop-in ready for larger projects
* **Clarity** – Easy to read, modify, and extend
* **Performance** – Zero JavaScript dependency

## Ideal Use Cases

Baroque is ideal for:

* Editorial websites and blogs
* News or magazine platforms
* Corporate content hubs
* Marketing websites
* CMS-driven article feeds
* UI/UX demonstrations and portfolios

## Extensibility & Integration

While built with plain HTML and CSS, this component can be **easily integrated** into:

* WordPress themes (as a template part or block)
* React or Vue applications (converted into a component)
* Static site generators such as Astro or Eleventy

The isolated class architecture ensures minimal refactoring when ported into larger ecosystems.


## Folder Structure

```
Baroque/
├── index.html
├── styles.css
└── preview.png
```

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/lefajmofokeng/Baroque.git
   ```

2. Open `index.html` in your browser or serve locally.

No build tools or dependencies are required.

## License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this code for personal or commercial projects with proper attribution.
