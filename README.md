# Draft Punk Website

A modern, minimalist website with a dark theme featuring dynamic logo carousel, responsive navigation, and clean typography.

## File Structure

```
draft-punk/
│
├── index.html          # Homepage with logo carousel
├── about.html          # About page
├── imprint.html        # Legal/Imprint page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
│
└── images/             # Image directory
    ├── draftpunk-logo.png
    ├── draftpunklogoballoon.png
    └── draftpunklogofluff.png
```

## Features

- **Responsive Design**: Mobile-first approach with hamburger menu
- **Logo Carousel**: Auto-rotating logo variations on homepage (1-second intervals)
- **Typography**: 
  - Cantata One (serif) for headings
  - Lato (sans-serif) for body text
- **Material Icons**: Both Outlined and Sharp variants available
- **Dark Theme**: Modern dark color scheme (#121212 background)
- **SEO Optimized**: Meta descriptions and semantic HTML

## Setup Instructions

1. **Create project directory**:
   ```bash
   mkdir draft-punk
   cd draft-punk
   ```

2. **Add all files**:
   - Save all HTML files (index.html, about.html, imprint.html)
   - Save styles.css
   - Save script.js
   - Create an `images/` folder and add your logo images

3. **Update content**:
   - Replace placeholder text in imprint.html with your actual information
   - Update copyright year if needed
   - Customize About page content as desired

## Browser Compatibility

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## External Dependencies

All dependencies are loaded from CDNs:
- Google Fonts (Cantata One, Lato)
- Material Icons (Outlined & Sharp)

## Customization

### Colors
Edit in `styles.css`:
```css
body {
    background-color: #121212;  /* Dark background */
    color: #e0e0e0;            /* Light text */
}
```

### Carousel Speed
Edit in `script.js`:
```javascript
setInterval(nextImage, 1000);  // Change 1000 to desired milliseconds
```

### Navigation Items
Edit nav menu in each HTML file:
```html
<ul class="nav-menu">
    <li><a href="index.html" class="nav-link">Home</a></li>
    <li><a href="about.html" class="nav-link">About</a></li>
    <li><a href="imprint.html" class="nav-link">Imprint</a></li>
</ul>
```

## Using Material Icons

Add icons anywhere in your HTML:
```html
<!-- Outlined style -->
<span class="material-icons-outlined">home</span>

<!-- Sharp style -->
<span class="material-icons-sharp">favorite</span>
```

Browse available icons at: https://fonts.google.com/icons

## License

© 2024 Draft Punk. All rights reserved.

## Contact

- Website: draftpunk.me
- Email: contact@draftpunk.me
