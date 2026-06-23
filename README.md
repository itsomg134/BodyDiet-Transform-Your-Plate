# BodyDiet – Transform Your Plate

**BodyDiet** is a modern, responsive landing page designed for a diet and nutrition platform. It showcases personalized diet plans, healthy recipes, and a clean, inviting interface to help users start their wellness journey.

<img width="1890" height="2656" alt="image" src="https://github.com/user-attachments/assets/51dd7306-6364-4053-a71c-0efd6c4e7bfd" />

---

## Features

- **Fully Responsive** – Looks great on desktop, tablet, and mobile.
- **Clean & Organic Design** – Calming green palette with a focus on readability.
- **Diet Plan Cards** – Highlight different diet types (Keto, Plant-based, High Protein, Low Carb).
- **Recipe Grid** – Showcase healthy meals with prep time and dietary tags.
- **Interactive Elements** – Subtle hover animations and modern UI components.
- **FontAwesome Icons** – Rich visual language without heavy images.
- **No External Dependencies** – Pure HTML & CSS (self-contained).

---

## Tech Stack

- **HTML5** – Semantic markup.
- **CSS3** – Custom styles with flexbox/grid, no frameworks.
- **Font Awesome 6** – Icon library for visual elements.

---

## Project Structure

```
body-diet-website/
├── index.html          # Main HTML file (contains all CSS inline)
└── README.md           # This file
```

> **Note:** All styles are embedded in `<style>` within the HTML for simplicity. For production, consider extracting CSS to a separate file.

---

## Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/body-diet-website.git
cd body-diet-website
```

### 2. Open the project
Simply open `index.html` in your browser:
```bash
open index.html   # macOS
start index.html  # Windows
xdg-open index.html # Linux
```

### 3. Customize
- **Colors:** Search for `#2b7a4b` (primary green) and replace with your brand color.
- **Content:** Update text, recipes, and diet plans inside the `<body>`.
- **Logo:** Change the FontAwesome icon or replace with your own image.

---

## Customization Guide

### Change the hero image
Replace the emoji/FontAwesome placeholder in the `.hero-image` div with an `<img>` tag:
```html
<div class="hero-image">
  <img src="your-image.jpg" alt="Healthy meal" />
</div>
```

### Add or remove diet plans
Copy a `.plan-card` div inside `.plan-grid` and modify the content.

### Update recipe items
Edit the `.recipe-item` blocks in the `.recipe-grid` section.

---

##  Deployment

Deploy for free on:
- **Netlify** – Drag and drop the folder.
- **Vercel** – `vercel --prod`
- **GitHub Pages** – Push to `gh-pages` branch.

---

## Contributing

Contributions are welcome!  
1. Fork the repository.  
2. Create a feature branch: `git checkout -b feature/amazing-feature`.  
3. Commit your changes: `git commit -m 'Add some amazing feature'`.  
4. Push: `git push origin feature/amazing-feature`.  
5. Open a Pull Request.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

##  Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)

Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)

Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)

LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)

Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)
