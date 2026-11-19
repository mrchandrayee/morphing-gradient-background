# Morphing Gradient Background

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/morphing-gradient-background/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable recreation of the 5-second uploaded video, titled **Morphing Gradient Background**.

## Run
Open `index.html` directly in a modern browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Video-visible source transcribed
The video visibly shows this HTML element:

```html
<div class="morphing-bg"></div>
```

And these CSS declarations:

```css
.morphing-bg {
  width: 750px;
  height: 300px;
  background: linear-gradient(45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
  background-size: 400% 400%;
  animation: gradient 8s ease infinite, morph 5s ease infinite;
  border-radius: 20px;
  transform-style: preserve-3d;
  box-shadow: 5px 15px 20px 0 rgba(0, 0, 0, 0.4);
  border: 2.5px solid #eee;
}
```

The video does not show the `@keyframes gradient` or `@keyframes morph` definitions. They are added as a clearly marked implementation so the demo runs and produces the visible animated gradient/morphing effect. The displayed HTML/CSS cards are included in the page itself.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
