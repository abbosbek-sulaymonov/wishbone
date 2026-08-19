# Wishbone+Partners - Architecture Firm Website

![Project Banner](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)

A modern, responsive website for an architecture firm showcasing beautiful design principles with smooth animations and professional aesthetics.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Technologies](#technologies)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Performance](#performance)
- [Accessibility](#accessibility)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview

Wishbone+Partners is a modern, fully responsive architecture firm website template that emphasizes beautiful but functional design. The website showcases projects, team members, and company information with smooth animations and professional styling.

### Key Highlights

- **Modern Design**: Clean, professional aesthetic with focus on usability
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Engaging CSS animations throughout the site
- **Performance Optimized**: Fast loading times with optimized assets
- **SEO Friendly**: Semantic HTML structure for better search engine visibility

## ✨ Features

### Design Features

- ✅ Modern minimalist design
- ✅ Smooth scroll animations
- ✅ Hover effects on interactive elements
- ✅ Professional color scheme
- ✅ Typography using Poppins font family
- ✅ Sticky navigation bar with blur effect
- ✅ Image zoom effects on hover
- ✅ Responsive image galleries

### Functionality

- ✅ Mobile-friendly hamburger menu
- ✅ Smooth page scrolling
- ✅ Interactive project showcases
- ✅ Team member cards
- ✅ Contact section
- ✅ Social media integration
- ✅ Featured projects section
- ✅ Client testimonials

### Technical Features

- ✅ CSS Custom Properties (variables)
- ✅ Flexbox layouts
- ✅ CSS Grid where applicable
- ✅ Mobile-first responsive design
- ✅ Optimized animations
- ✅ Cross-browser compatibility
- ✅ Accessibility support

## 🎬 Demo

### Desktop View

The website features a full-screen hero section, elegant navigation, and smooth transitions between sections.

### Mobile View

Responsive design adapts perfectly to mobile devices with a collapsible navigation menu and optimized content layout.

## 🛠 Technologies

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with animations
- **Font Awesome 4.7.0** - Icon library
- **Google Fonts** - Poppins font family
- **Vanilla JavaScript** - (Ready for enhancement)

## 📦 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML/CSS

### Quick Start

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/wishbone-partners.git
   cd wishbone-partners
   ```

2. **Project structure should look like this:**

   ```
   wishbone-partners/
   ├── index.html
   ├── styles/
   │   └── style.css
   ├── images/
   │   ├── IMAGE.png
   │   ├── main1.png
   │   ├── main2.png
   │   ├── main3.png
   │   ├── item1.png
   │   ├── item2.png
   │   ├── item3.png
   │   ├── person.png
   │   ├── Sketching-Icon.png
   │   ├── Finalizing-Icon.png
   │   ├── ic1.png
   │   ├── ic2.png
   │   ├── ic3.png
   │   ├── Combined-Shape (1).png
   │   ├── Path.png
   │   ├── Shape.png
   │   └── Path (1).png
   └── README.md
   ```

3. **Open in browser**
   - Simply double-click `index.html` or
   - Use a local server (recommended):

     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js
     npx http-server

     # Using PHP
     php -S localhost:8000
     ```

4. **View in browser**
   - Navigate to `http://localhost:8000`

## 📁 Project Structure

```
wishbone-partners/
│
├── index.html              # Main HTML file
├── styles/
│   └── style.css          # Main stylesheet with animations
├── images/                # Image assets directory
│   ├── IMAGE.png          # Hero section image
│   ├── main1.png          # Banner 1 image
│   ├── main2.png          # Banner 2 image
│   ├── main3.png          # Banner 3 image
│   ├── item1.png          # Featured project 1
│   ├── item2.png          # Featured project 2
│   ├── item3.png          # Featured project 3
│   ├── person.png         # Team member avatar
│   ├── Sketching-Icon.png # Process icon
│   ├── Finalizing-Icon.png# Process icon
│   ├── ic1.png            # Client logo
│   ├── ic2.png            # Client logo
│   ├── ic3.png            # Client logo
│   ├── Combined-Shape.png # Client logo
│   ├── Path.png           # Social icon (Twitter)
│   ├── Shape.png          # Social icon (Facebook)
│   └── Path (1).png       # Social icon (Instagram)
│
└── README.md              # Project documentation
```

## 🎨 Customization

### Color Scheme

Edit CSS custom properties in `styles/style.css`:

```css
:root {
  --color-primary: #1b1a1a; /* Primary dark color */
  --color-secondary: #645c55; /* Secondary gray */
  --color-accent: #403e3b; /* Accent brown */
  --color-bg-light: #ece7e4; /* Light background */
  --color-bg-gray: #f7f7f7; /* Gray background */
  --color-bg-tan: #cec4bc; /* Tan background */
  --color-white: #ffffff; /* White */
}
```

### Typography

Change font by updating the Google Fonts import:

```css
@import url("https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap");

* {
  font-family: "YourFont", sans-serif;
}
```

### Animations

Adjust animation timing in CSS:

```css
:root {
  --transition-base: 0.3s ease;
  --transition-smooth: 0.5s cubic-bezier(0.4, 0, 0.2, 1);
}
```

### Content

1. **Company Name**: Update in `index.html`

   ```html
   <span class="thin">YourCompany</span><span class="bold">+Partners</span>
   ```

2. **Navigation Links**: Modify in the `nav` section
3. **Images**: Replace images in the `images/` folder
4. **Text Content**: Update Lorem ipsum text with your content
5. **Social Links**: Update footer social media links

## 🌐 Browser Support

| Browser | Version   |
| ------- | --------- |
| Chrome  | ✅ Latest |
| Firefox | ✅ Latest |
| Safari  | ✅ Latest |
| Edge    | ✅ Latest |
| Opera   | ✅ Latest |

### Mobile Support

- ✅ iOS Safari 12+
- ✅ Chrome Mobile
- ✅ Firefox Mobile
- ✅ Samsung Internet

## ⚡ Performance

### Optimization Tips

1. **Image Optimization**
   - Compress images using tools like TinyPNG
   - Use WebP format for better compression
   - Lazy load images below the fold

2. **CSS Optimization**
   - Minify CSS for production
   - Remove unused CSS rules
   - Use CSS containment for better rendering

3. **Loading Performance**
   - Add `loading="lazy"` to images
   - Preload critical fonts
   - Use CDN for Font Awesome

### Example Implementation:

```html
<!-- Lazy loading images -->
<img src="image.jpg" alt="Description" loading="lazy" />

<!-- Preload critical fonts -->
<link
  rel="preload"
  href="fonts/poppins.woff2"
  as="font"
  type="font/woff2"
  crossorigin
/>
```

## ♿ Accessibility

The website follows WCAG 2.1 guidelines:

- ✅ Semantic HTML structure
- ✅ Proper heading hierarchy
- ✅ Alt text for images
- ✅ Keyboard navigation support
- ✅ Focus indicators
- ✅ Color contrast ratios
- ✅ Reduced motion support

### Reduced Motion Support

Users who prefer reduced motion will see simplified animations:

```css
@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}
```

## 📱 Responsive Breakpoints

```css
/* Desktop First */
@media only screen and (max-width: 992px) {
  /* Tablet */
}
@media only screen and (max-width: 768px) {
  /* Small Tablet */
}
@media only screen and (max-width: 576px) {
  /* Mobile */
}
```

## 🚀 Deployment

### GitHub Pages

1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select branch (main) and folder (root)
4. Save and wait for deployment

### Netlify

1. Connect your GitHub repository
2. Build command: (leave empty)
3. Publish directory: `/`
4. Deploy

### Vercel

```bash
npm i -g vercel
vercel
```

### Traditional Hosting

Upload all files to your web server via FTP/SFTP.

## 🔧 Advanced Features (Future Enhancements)

### Potential Additions:

- [ ] Contact form with validation
- [ ] Project filtering/search
- [ ] Lightbox for images
- [ ] Scroll-triggered animations
- [ ] Dark mode toggle
- [ ] Multi-language support
- [ ] Blog section
- [ ] Case studies
- [ ] Virtual tour integration
- [ ] Client testimonial carousel

## 📝 Customization Examples

### Adding a New Section

```html
<div class="new-section">
  <h2>New Section Title</h2>
  <p>Section content goes here...</p>
</div>
```

```css
.new-section {
  padding: 100px 140px;
  background: var(--color-bg-gray);
  animation: fadeIn 0.8s ease;
}
```

### Adding Animation to Element

```css
.your-element {
  animation: fadeInLeft 0.8s ease;
}
```

## 🐛 Known Issues

- Mobile menu requires hover (consider adding click handler)
- Some browsers may need vendor prefixes
- IE11 not fully supported (modern browsers only)

## 💡 Tips & Tricks

1. **Use CSS Variables**: Easy to maintain and update colors
2. **Optimize Images**: Always compress before uploading
3. **Test Responsiveness**: Use browser dev tools
4. **Keep It Simple**: Don't overuse animations
5. **Accessibility First**: Always test with keyboard navigation

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines

- Follow existing code style
- Comment your code
- Test on multiple browsers
- Update README if needed
- Keep commits atomic and descriptive

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2024 Wishbone+Partners

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 📞 Contact

**Developer**

- GitHub: [@abbosbek-sulaymonov](https://github.com/abbosbek-sulaymonov)
- LinkedIn: [Abbosbek Sulaymonov](https://linkedin.com/in/yourprofile)
- Email: abek01sulaymonov@gmail.com

## 🙏 Acknowledgments

- **Font Awesome** - Icon library
- **Google Fonts** - Poppins font family
- **Unsplash/Pexels** - Stock images (if used)
- **Community Contributors** - Thank you for your contributions!

## 📚 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [Can I Use](https://caniuse.com/)
- [Web.dev](https://web.dev/)
- [A11y Project](https://www.a11yproject.com/)

## 📊 Project Status

Current Version: **1.0.0**

Status: **Active Development**

Last Updated: **November 2024**

---

<div align="center">

**Made with ❤️ by Wishbone+Partners**

⭐ Star this repo if you find it helpful!

[Report Bug](https://github.com/yourusername/wishbone-partners/issues) · [Request Feature](https://github.com/yourusername/wishbone-partners/issues)

</div>

---

### Quick Links

- [Live Demo](#) | [Documentation](#) | [API](#) | [Changelog](#)

### Version History

- **v1.0.0** (Nov 2024)
  - Initial release
  - Modern CSS with animations
  - Fully responsive design
  - Accessibility improvements

---

**Happy Coding! 🚀**
