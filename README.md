# YounesHatti.com

A minimalist personal website featuring Islamic geometric patterns, glassmorphism effects, and a dark theme with royal green accents.

## Design Features

- **Islamic Geometric Patterns**: Animated background with traditional Islamic tile patterns
- **Glassmorphism**: Beautiful transparent glass-style cards with backdrop blur
- **Dark Theme**: Elegant dark background with royal green (#0f6342) and gold accents
- **Minimalist**: Clean, focused design with only HTML and CSS
- **Responsive**: Works beautifully on all devices

## Project Structure

```
YounesHatti.com/
├── index.html              # Main homepage
├── css/
│   └── style.css          # All styles (glassmorphism, patterns, animations)
├── assets/
│   ├── images/            # Your photos and images
│   │   └── YounesHATTI Photo.jpg
│   └── patterns/          # Pattern assets (if needed)
├── blog/
│   ├── README.md          # Instructions for adding blog posts
│   ├── template.html      # Template for new blog posts
│   └── (your-posts.html)  # Your blog posts go here
└── README.md              # This file
```

## Quick Start Guide

### 1. Update Google Analytics (Optional)

If you want to track website analytics:
1. Get your Google Analytics ID from https://analytics.google.com
2. In `index.html`, replace `YOUR_GA_ID` with your actual ID
3. Do the same in `blog/template.html`

If you don't need analytics, you can remove the Google Analytics script section.

### 2. Update Your Information

Edit `index.html`:
- Change the tagline: `<p class="tagline">Developer & Creator</p>`
- Update the About section content
- Verify your GitHub and X (Twitter) links are correct

### 3. Adding Blog Posts

See detailed instructions in `blog/README.md`

**Quick steps:**
1. Copy `blog/template.html` to `blog/your-post-name.html`
2. Edit your new file with your content
3. Add the post link to `index.html` in the blog section

## Customization

### Colors

The color scheme is defined in `css/style.css` under `:root` variables:

```css
--royal-green: #0f6342;
--royal-green-light: #1a8f5e;
--gold-accent: #d4af37;
--dark-bg: #0a0f0d;
```

You can easily change these to customize the look!

### Adding Images

Place images in `assets/images/` and reference them:
```html
<img src="assets/images/your-image.jpg" alt="Description">
```

## Maintenance

This website is designed to be extremely easy to maintain:
- **No build process** - just HTML and CSS
- **No dependencies** - no npm, webpack, or frameworks
- **Simple structure** - easy to navigate and understand
- **Well commented** - code is organized and documented

## Social Links

Current links in the website:
- GitHub: https://github.com/YounesHatti
- X (Twitter): https://x.com/YOUNESxHATTI

To update these, edit the social links section in `index.html`.

## Browser Support

Works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2026 Younes Hatti. All rights reserved.