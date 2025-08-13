# TechFlow Pro - Responsive Landing Page

A modern, responsive landing page for a fictional tech product built with HTML, CSS, and JavaScript. Features a clean design with red, black, and white theme, dark/light mode toggle, and mobile-first responsive design.

## 🚀 Features

### Design & Layout
- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Modern UI**: Clean, professional design with smooth animations
- **Theme Toggle**: Light and dark mode support with localStorage persistence
- **Color Scheme**: Red, black, and white theme as requested

### Sections
- **Hero Section**: Compelling headline with call-to-action buttons
- **Features**: 6 feature cards with icons and descriptions
- **Testimonials**: Customer testimonials with avatar placeholders
- **Pricing**: 3-tier pricing structure with featured plan
- **Call-to-Action**: Final conversion section
- **Footer**: Comprehensive footer with links and social media

### Interactive Features
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Button Animations**: Hover and click effects on all buttons
- **Scroll Animations**: Elements animate in as they come into view
- **Theme Persistence**: User's theme preference is saved

### Technical Features
- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Custom Properties**: Theme variables for easy customization
- **Intersection Observer**: Performance-optimized animations
- **Throttled Events**: Optimized scroll handling
- **Accessibility**: ARIA labels, keyboard navigation, focus styles

## 📁 Project Structure

```
Task 4 Landing Page/
├── index.html          # Main HTML structure
├── styles.css          # All CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: 
  - CSS Grid and Flexbox for layouts
  - CSS Custom Properties (variables)
  - Media queries for responsiveness
  - Animations and transitions
- **JavaScript (ES6+)**:
  - DOM manipulation
  - Event handling
  - LocalStorage for theme persistence
  - Intersection Observer API
  - Performance optimizations

## 🎨 Design System

### Colors
- **Primary Red**: `#dc2626` (Light) / `#ef4444` (Dark)
- **Secondary Black**: `#1f2937` (Light) / `#f3f4f6` (Dark)
- **Background**: `#ffffff` (Light) / `#111827` (Dark)
- **Surface**: `#f9fafb` (Light) / `#1f2937` (Dark)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Font Weights**: 300, 400, 500, 600, 700
- **Responsive Sizing**: Fluid typography with CSS custom properties

### Spacing
- **Consistent Scale**: 0.5rem, 1rem, 1.5rem, 2rem, 3rem, 4rem
- **Responsive**: Adapts to screen size

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: > 768px

## 🚀 Getting Started

1. **Clone or Download** the project files
2. **Open** `index.html` in a web browser
3. **Test** the responsive design by resizing the browser window
4. **Try** the theme toggle button in the navigation
5. **Test** mobile navigation on smaller screens

## 🎯 Key Features Implementation

### Theme Toggle
```javascript
function toggleTheme() {
    if (body.classList.contains('light-theme')) {
        body.classList.remove('light-theme');
        body.classList.add('dark-theme');
        // Update icon and save preference
    }
}
```

### Mobile Navigation
```javascript
function toggleMobileMenu() {
    navMenu.classList.toggle('active');
    navToggle.classList.toggle('active');
}
```

### Smooth Scrolling
```javascript
function smoothScrollToSection(e) {
    e.preventDefault();
    const targetId = this.getAttribute('href');
    const targetSection = document.querySelector(targetId);
    // Smooth scroll to target section
}
```

## 🎨 Customization

### Changing Colors
Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #dc2626;    /* Change main red color */
    --secondary-color: #1f2937;  /* Change secondary color */
    /* ... other variables */
}
```

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add navigation link if needed
4. Update JavaScript if interactive features are required

### Modifying Content
- Update text content in `index.html`
- Replace Font Awesome icons with different ones
- Modify pricing plans, features, or testimonials

## 🔧 Browser Support

- **Chrome**: 60+
- **Firefox**: 55+
- **Safari**: 12+
- **Edge**: 79+

## 📊 Performance Features

- **Optimized Images**: Using Font Awesome icons instead of images
- **CSS Optimization**: Efficient selectors and minimal reflows
- **JavaScript Optimization**: Throttled scroll events, efficient DOM queries
- **Loading Performance**: Minimal external dependencies

## ♿ Accessibility Features

- **Semantic HTML**: Proper heading hierarchy and landmarks
- **ARIA Labels**: Screen reader support for interactive elements
- **Keyboard Navigation**: Full keyboard accessibility
- **Focus Indicators**: Clear focus styles for all interactive elements
- **Color Contrast**: WCAG AA compliant color combinations

## 🚀 Future Enhancements

- **Contact Form**: Add a functional contact form
- **Blog Section**: Add a blog or news section
- **Multi-language Support**: Internationalization features
- **PWA Features**: Service worker for offline functionality
- **Analytics Integration**: Google Analytics or similar
- **A/B Testing**: Multiple landing page variants

## 📝 License

This project is created for educational purposes. Feel free to use and modify as needed.

## 🤝 Contributing

1. Fork the project
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or issues, please check the code comments or create an issue in the repository.

---

**Built with ❤️ using HTML, CSS, and JavaScript** 