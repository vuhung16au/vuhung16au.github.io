# Personal Portfolio Website

A modern, responsive personal website built with HTML, CSS, and JavaScript. This website showcases professional experience, projects, skills, and provides multiple ways for visitors to connect.

## Features

- **Responsive Design**: Optimized for all device sizes
- **Dark Mode**: Toggle between light and dark themes
- **SEO Optimized**: Meta tags and semantic HTML structure
- **Modern UI**: Clean, professional design with smooth animations
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Enhanced user experience with smooth scrolling
- **Contact Form**: Interactive contact form for visitor inquiries

## Pages

### 1. Home (`index.html`)
- Hero section with introduction
- About me section with profile and skills
- Quick links to other sections
- Call-to-action buttons

### 2. About (`about.html`)
- Detailed personal information
- Professional background
- Key skills and expertise
- Personal philosophy

### 3. Projects (`projects.html`)
- Portfolio of projects
- Project descriptions and technologies
- Links to demos and source code
- Project categories

### 4. Experience (`experience.html`)
- Work experience timeline
- Job descriptions and achievements
- Educational background
- Certifications and training

### 5. Skills (`skills.html`)
- Technical skills with proficiency levels
- Programming languages
- Web technologies
- Tools and software
- Soft skills

### 6. Contact (`contact.html`)
- Contact form
- Contact information
- Social media links
- Alternative contact methods

### 7. Teaching (`teaching.html`)
- Teaching experience
- Course offerings
- Educational philosophy
- Learning approach

### 8. Blog (`blog.html`)
- Featured blog posts
- Latest articles
- Blog categories
- Reading recommendations

### 9. Career (`career.html`)
- Career goals and vision
- Professional achievements
- Development plans
- Future aspirations

## File Structure

```
├── index.html              # Home page
├── about.html              # About page
├── projects.html           # Projects page
├── experience.html         # Experience page
├── skills.html             # Skills page
├── contact.html            # Contact page
├── teaching.html           # Teaching page
├── blog.html               # Blog page
├── career.html             # Career page
├── assets/
│   ├── css/
│   │   ├── style.css      # Main stylesheet
│   │   └── dark-mode.css  # Dark theme styles
│   ├── js/
│   │   └── main.js        # JavaScript functionality
│   └── img/               # Image assets
└── README.md              # Documentation
```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)**: Interactive functionality and theme switching
- **CSS Variables**: For consistent theming and easy customization

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Setup and Customization

### 1. Basic Setup
1. Clone or download the repository
2. Open `index.html` in your web browser
3. Customize content in the HTML files

### 2. Content Customization
- Replace "Your Name" with your actual name throughout the files
- Update profile information, skills, and experience
- Add your own projects and blog posts
- Update contact information and social media links

### 3. Styling Customization
- Modify colors in CSS variables (in `:root` selector)
- Adjust layout and spacing in `style.css`
- Customize dark mode colors in `dark-mode.css`

### 4. Adding Images
- Place your images in the `assets/img/` directory
- Replace placeholder emojis with actual images
- Update image paths in HTML files

## Key Features Explained

### Dark Mode
The website includes a dark mode toggle that:
- Switches between light and dark themes
- Remembers user preference using localStorage
- Automatically adjusts all colors and components

### Responsive Design
- Mobile-first approach
- CSS Grid and Flexbox for layouts
- Media queries for different screen sizes
- Touch-friendly navigation

### SEO Optimization
- Semantic HTML structure
- Meta tags for description and keywords
- Proper heading hierarchy
- Alt text for images
- Clean URL structure

### Performance
- Optimized CSS with minimal redundancy
- Efficient JavaScript with event delegation
- Smooth animations using CSS transitions
- Lazy loading for better performance

## Customization Tips

### Adding New Pages
1. Copy an existing HTML file
2. Update the navigation menu
3. Modify content and sections
4. Ensure consistent styling

### Modifying Colors
Update the CSS variables in `:root`:
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --accent-color: #your-color;
    /* ... other variables */
}
```

### Adding New Sections
1. Use existing CSS classes for consistency
2. Follow the established grid system
3. Maintain responsive behavior
4. Test on different screen sizes

## Deployment

### GitHub Pages
1. Push code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Choose source branch (usually `main`)
4. Your site will be available at `username.github.io/repository-name`

### Other Hosting
- Upload files to any web hosting service
- Ensure all file paths are correct
- Test functionality after deployment

## Browser Testing

Test the website on:
- Desktop browsers (Chrome, Firefox, Safari, Edge)
- Mobile devices (iOS Safari, Android Chrome)
- Different screen sizes and orientations
- Various network conditions

## Performance Optimization

- Minimize image sizes
- Use appropriate image formats (WebP, SVG)
- Enable gzip compression on server
- Implement caching strategies
- Monitor Core Web Vitals

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- Screen reader compatibility
- Color contrast compliance

## Future Enhancements

- Blog post management system
- Project filtering and search
- Contact form backend integration
- Analytics integration
- Multi-language support
- Progressive Web App features

## Support

For questions or issues:
1. Check the documentation
2. Review browser console for errors
3. Validate HTML and CSS
4. Test on different devices

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This is a template website. Remember to:
- Replace placeholder content with your actual information
- Update meta tags and SEO information
- Add your own images and branding
- Test thoroughly before deployment
- Keep content updated and relevant
