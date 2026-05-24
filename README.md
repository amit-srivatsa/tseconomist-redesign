# TSEconomist Web Redesign Pitch Hub 📖

Welcome to the public repository for the interactive **TSEconomist** web redesign. This project showcases a modern, responsive, and performance-optimized digital layout designed specifically for prestigious student-run academic journals.

---

## Project Overview 🏛️

I was a founding member of this magazine back in 2012 when I studied my M1 Economics at the Toulouse School of Economics (TSE). Over a decade later, I noticed the website was still running on a layout nearly identical to the original system I designed.

To bring things full circle, I built this modern, responsive web application as a gift of goodwill to the current student editorial board. It serves as an interactive prototyping hub where users can instantly swap brand palettes and experiment with structural changes.

---

## Interactive Features 🎨

- **Three premium academic palettes**: Users can toggle between Scholarly Blue, Deep Crimson, and Emerald themes in real-time.
- **Intelligent dark mode**: The prototype includes dynamic contrast rules that adjust text legibility and brand highlights automatically for night reading.
- **Interactive cover switcher**: Swap featured issue spotlights to preview how different cover concepts look on the live grid.
- **Dual-core editorial hierarchy**: The interface clearly separates heavy academic research from casual student life guides.

---

## Technical Architecture 💻

I designed this hub using a single-file architecture strategy to ensure lightning-fast loading speeds and zero build-step friction.

- **Tailwind CSS**: Used for fluid grids, modern spacing tokens, and responsive utility layouts.
- **Dynamic CSS Variables**: All color themes are managed through CSS custom properties bound to a light-weight JavaScript engine.
- **Zero Dependencies**: The prototype runs completely in the browser without requiring `npm`, Webpack, or external libraries.

---

## How to Customize the Colors for Your Own Project 🛠️

You can easily adapt this layout for your own school blog, portfolio, or student magazine. Simply open [index.html](index.html) and edit the `:root` variables inside the `<style>` tag:

```css
:root {
  /* Replace these with your own brand hexadecimal colors */
  --theme-bg: #F7F5EF;
  --theme-text: #212121;
  --theme-primary: #1B2A3B;
  --theme-accent: #869E66;
}
```

The dynamic theme engine in the `<script>` tag will automatically map your new values to the entire layout grid.

---

## Live Deployment Guide 🌐

1. **Fork this repository** to your own public GitHub account.
2. **Ensure your main entry file** is named exactly `index.html` in the root folder.
3. **Go to your repository settings** and navigate to the **Pages** menu on the left.
4. **Select the main branch** under the build source settings and hit save.
5. Your customized interactive hub will be live at your public URL in less than a minute.

---

## License ⚖️

This project is open-source and free to use under the **MIT License**. Feel free to copy, modify, and build upon it to empower your own academic communities.
