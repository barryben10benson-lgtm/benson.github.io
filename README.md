# Amore Benson Photography Website

A modern, professional photography website for Amore Benson Photography featuring family and wedding photoshoot services.

## Features

- **Homepage**: Beautiful hero section, about section, services preview, and portfolio gallery
- **Services Page**: Detailed information about Family Photoshoot and Wedding Photoshoot services with galleries
- **Contact Page**: Contact form with validation and contact information
- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean, professional design with smooth animations
- **Professional Images**: High-quality placeholder images from Unsplash

## File Structure

```
Website/
├── index.html          # Homepage
├── services.html       # Services page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## Getting Started

1. Simply open `index.html` in your web browser to view the website
2. No build process or dependencies required - it's a pure HTML/CSS/JavaScript website

## Pages

### Homepage (index.html)
- Hero section with call-to-action
- About section
- Services preview cards
- Portfolio gallery

### Services Page (services.html)
- Family Photoshoot service details
- Wedding Photoshoot service details
- Image galleries for each service
- Call-to-action sections

### Contact Page (contact.html)
- Contact information
- Contact form with validation
- Map placeholder section

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #e74c3c;
    --accent-color: #f39c12;
    /* ... */
}
```

### Images
Replace the Unsplash image URLs with your own professional photography images. The images are referenced in the HTML files.

### Contact Information
Update the contact details in:
- `contact.html` (contact section)
- Footer sections in all HTML files

### Form Submission
The contact form currently shows a success message. To actually send emails, you'll need to:
1. Set up a backend service (PHP, Node.js, etc.)
2. Update the form submission handler in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- Images are loaded from Unsplash (placeholder images)
- Replace with your own professional photography images
- The contact form requires backend integration for actual email sending
- All pages are fully responsive and mobile-friendly

## License

© 2024 Amore Benson Photography. All rights reserved.

