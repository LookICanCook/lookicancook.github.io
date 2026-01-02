# Look I Can Cook - Marketing Landing Page

This is a static marketing landing page for Look I Can Cook, inspired by Pinterest's design. The page is completely self-contained with no dependencies on the rest of the repository.

## Structure

```
landingpage/
├── index.html          # Main landing page
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # Interactive features
├── assets/
│   └── images/
│       ├── logo.svg           # App logo
│       ├── logo-text.svg      # Logo with text
│       ├── favicon.png        # Favicon
│       ├── screenshot-1.png   # Placeholder (replace with actual screenshot)
│       ├── screenshot-2.png   # Placeholder (replace with actual screenshot)
│       ├── screenshot-3.png   # Placeholder (replace with actual screenshot)
│       └── screenshot-4.png   # Placeholder (replace with actual screenshot)
└── README.md           # This file
```

## Replacing Screenshots

The landing page includes 4 placeholder screenshots that you should replace with actual app screenshots:

1. **screenshot-1.png** - Recipe extraction from photos (used in hero section)
2. **screenshot-2.png** - Pinterest-style folder organization
3. **screenshot-3.png** - Recipe search and discovery
4. **screenshot-4.png** - Recipe details view

### Recommended Screenshot Specifications:
- **Format**: PNG or JPG
- **Dimensions**: 800x600px or similar aspect ratio
- **File size**: Optimized for web (under 500KB each)
- **Content**: Clear, high-quality screenshots showing the app's key features

Simply replace the placeholder files in `assets/images/` with your actual screenshots, keeping the same filenames.

## Updating URLs

Update the following URLs in `js/main.js`:

1. **webAppUrl** - URL to your live web app
2. **loginUrl** - URL to the login page
3. **signupUrl** - URL to the signup page

Currently these are set to `#` as placeholders. Update them to your actual URLs.

## Local Development

To view the page locally, simply open `index.html` in a web browser. No build process or server is required.

For a better development experience, you can use a simple HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Deployment

This is a static site that can be deployed to any static hosting service:

- **Netlify**: Drag and drop the `landingpage` folder
- **Vercel**: Deploy the `landingpage` directory
- **GitHub Pages**: Push to a repository and enable Pages
- **AWS S3**: Upload files to an S3 bucket with static website hosting
- **Any web server**: Upload files via FTP/SFTP

## Customization

### Colors
The color scheme is defined in CSS variables at the top of `css/styles.css`:

```css
:root {
    --primary: #e70b5a;
    --primary-light: #f8a5c2;
    --primary-dark: #c4084a;
    /* ... */
}
```

### Content
Edit `index.html` to update text, add sections, or modify the structure.

### Styling
All styles are in `css/styles.css`. The design is responsive and mobile-first.

## Browser Support

The page uses modern CSS and JavaScript features and supports:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

For older browsers, some features may need polyfills.

## Notes

- The page is fully self-contained with no external dependencies
- All assets are included in the `assets/` directory
- The design is responsive and works on mobile, tablet, and desktop
- Smooth scrolling and animations are included for better UX

