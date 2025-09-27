# Utkarsh Classes Inspired Website

A complete educational website inspired by Utkarsh Classes with modern design and functionality.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean design with Utkarsh's signature color scheme
- **Interactive Elements**: Smooth scrolling, hover effects, animations
- **Reusable Components**: Modular components for easy customization
- **Accessibility**: Built with accessibility best practices

## Structure

```
utkarsh-website/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Sections Included

1. **Header**: Navigation with logo, menu, search, contact info, login/signup
2. **Hero Section**: Main promotional area with CTA
3. **Stats Section**: Key metrics and achievements
4. **Features Section**: Platform benefits and features
5. **Course Categories**: Different exam types and courses
6. **Promo Section**: Course enrollment promotion
7. **Testimonials**: Student success stories
8. **CTA Section**: Call-to-action for enrollment
9. **Footer**: Complete site links and contact information

## Color Scheme

- Primary Yellow: #ffe066
- Dark: #111
- Background: #0b3142
- White: #fff
- Light Gray: #f5f5f5

## Customization

### Colors
Edit the CSS variables in `style.css` to change the color scheme:

```css
:root {
    --primary-color: #ffe066;
    --dark-color: #111;
    --background-color: #0b3142;
}
```

### Content
Edit `index.html` to modify:
- Text content
- Images (currently using placeholder images)
- Links and navigation items
- Contact information

### Styling
Modify `style.css` to adjust:
- Layout and spacing
- Typography
- Animations and transitions
- Responsive breakpoints

## JavaScript Features

- Mobile navigation toggle
- Smooth scrolling
- Stats counter animations
- Intersection Observer for scroll animations
- Form handling
- Search functionality (placeholder)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## Installation

1. Extract the ZIP file
2. Open `index.html` in your web browser
3. For development, use a local server (like Live Server in VS Code)

## Customization Guide

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding styles in `style.css`
3. Add JavaScript functionality in `script.js` if needed

### Changing Images
Replace placeholder images with your own:
- Logo: Update `.logo` img src
- Hero images: Update `.hero-image` src
- Testimonial photos: Update `.author-image` src
- Promo images: Update `.promo-image` src

### Adding Real Functionality
- Connect forms to backend APIs
- Implement actual search functionality
- Add user authentication
- Connect to payment gateways for course purchases

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts

## License

This template is created for educational and commercial use. Feel free to modify and use as needed.

## Support

For questions or customization help, please refer to the code comments or create an issue.
