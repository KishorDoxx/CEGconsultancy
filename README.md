# GlobalEdu Consultancy Website

A modern, responsive website for your educational consultancy offering IELTS, PTE, Japanese classes, and career counseling services.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Contact forms, mobile navigation, smooth scrolling
- **SEO Optimized**: Proper HTML structure and meta tags
- **Fast Loading**: Optimized CSS and JavaScript
- **Cross-browser Compatible**: Works on all modern browsers

## Services Included

1. **IELTS Classes**
   - Academic and General Training modules
   - Mock tests and practice materials
   - Personalized feedback and flexible scheduling

2. **PTE Classes**
   - Computer-based training
   - Real-time scoring feedback
   - Expert strategies and practice materials

3. **Japanese Classes**
   - All proficiency levels (beginner to advanced)
   - Native speakers
   - Cultural context and JLPT preparation

4. **Career Counseling**
   - Resume optimization
   - Interview coaching
   - Career planning and industry insights

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize content**: Edit the HTML file to update text, images, and information
3. **Modify styling**: Edit `styles.css` to change colors, fonts, and layout
4. **Add functionality**: Modify `script.js` for additional interactive features

## Customization Guide

### Changing Colors
The main color scheme uses CSS custom properties. You can modify these in `styles.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #48bb78;
    --text-color: #2d3748;
    --light-text: #4a5568;
}
```

### Updating Content
- **Company Name**: Change "GlobalEdu" throughout the HTML
- **Contact Information**: Update phone, email, and address in the contact section
- **Services**: Modify service descriptions and features
- **Testimonials**: Replace with real customer feedback
- **Statistics**: Update the numbers in the about section

### Adding Images
Replace the placeholder icons and image placeholders with your actual images:

```html
<!-- Replace this -->
<div class="image-placeholder">
    <i class="fas fa-users"></i>
    <p>Our Expert Team</p>
</div>

<!-- With this -->
<img src="path/to/your/image.jpg" alt="Our Expert Team" class="team-image">
```

### Form Integration
The contact form currently shows success messages. To make it functional:

1. **Backend Integration**: Connect to your server or form service
2. **Email Service**: Use services like Formspree, Netlify Forms, or your own backend
3. **Validation**: The form already includes client-side validation

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## Performance Features

- **Lazy Loading**: Images and sections load as needed
- **Smooth Animations**: CSS transitions and JavaScript animations
- **Optimized CSS**: Efficient selectors and minimal repaints
- **Mobile First**: Responsive design optimized for mobile devices

## SEO Features

- Semantic HTML structure
- Proper heading hierarchy (H1, H2, H3)
- Meta tags for social sharing
- Alt text for images
- Clean URL structure with anchor links

## Mobile Features

- Hamburger menu for mobile navigation
- Touch-friendly buttons and forms
- Responsive grid layouts
- Optimized typography for small screens

## Future Enhancements

Consider adding these features as your business grows:

1. **Blog Section**: Share educational tips and news
2. **Online Booking**: Calendar integration for class scheduling
3. **Student Portal**: Login system for enrolled students
4. **Payment Integration**: Online payment for classes
5. **Live Chat**: Customer support chat widget
6. **Multi-language Support**: For international students
7. **Progress Tracking**: Student performance dashboards

## Support

For customization help or questions:
1. Check the HTML comments for guidance
2. Review the CSS structure for styling changes
3. Examine the JavaScript functions for functionality
4. Test changes in multiple browsers

## License

This website template is created for your consultancy use. Feel free to modify and customize as needed.

---

**Note**: This is a static website. For dynamic features like user accounts, databases, or real-time updates, you'll need to integrate with a backend service or CMS.
