# Devesh Photography Website

A modern, futuristic photography website designed to match your camera lens logo with a sleek red and grey color scheme.

## 🎨 Features

### Design Features
- **Futuristic Design**: Modern, sleek interface with camera lens aesthetics
- **Logo Integration**: Custom CSS logo matching your red camera lens design
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: Engaging animations and transitions throughout
- **Dark Theme**: Professional dark theme with red accents

### Functionality
- **Portfolio Gallery**: Filterable portfolio with hover effects
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Smooth navigation between sections
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Interactive Elements**: Hover effects and animations

## 🚀 Quick Start

1. **Open the website**: Simply open `index.html` in your web browser
2. **No server required**: This is a static website that runs locally
3. **Customize content**: Edit the HTML file to update your information

## 📁 File Structure

```
Photograghy-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Customization Guide

### 1. Update Personal Information

Edit `index.html` to update:
- Your name and contact details
- About section content
- Services offered
- Portfolio images and descriptions

### 2. Change Colors

The color scheme is defined in `styles.css` using CSS variables:

```css
:root {
    --primary-red: #e63946;      /* Main red color */
    --dark-red: #c1121f;         /* Darker red */
    --primary-grey: #2b2d42;     /* Main grey */
    --dark-grey: #1a1b26;        /* Dark background */
    --light-grey: #8d99ae;       /* Light grey text */
}
```

### 3. Update Portfolio Images

Replace the Unsplash image URLs in `index.html` with your own images:

```html
<img src="your-image-url.jpg" alt="Your Description">
```

### 4. Modify Services

Update the services section in `index.html` to match your offerings:

```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-camera"></i>  <!-- Change icon -->
    </div>
    <h3>Your Service Name</h3>
    <p>Your service description</p>
    <div class="service-features">
        <span>Feature 1</span>
        <span>Feature 2</span>
        <span>Feature 3</span>
    </div>
</div>
```

### 5. Update Contact Information

Change the contact details in the contact section:

```html
<div class="contact-details">
    <h3>Phone</h3>
    <p>Your phone number</p>
</div>
```

## 🎨 Logo Customization

The logo is created using CSS and matches your camera lens design:

- **Red circular lens** with concentric grey circles
- **White flash dot** in the top-left corner
- **"DEVESH" text** in Orbitron font

To modify the logo colors, edit the CSS variables in `styles.css`.

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Technical Features

### CSS Features
- CSS Grid and Flexbox layouts
- CSS Custom Properties (variables)
- Smooth transitions and animations
- Backdrop filters for glass effects

### JavaScript Features
- Portfolio filtering system
- Smooth scrolling navigation
- Form validation and submission
- Intersection Observer for animations
- Mobile menu toggle
- Parallax scrolling effects

### Fonts Used
- **Orbitron**: Futuristic headings and logo
- **Rajdhani**: Body text and general content
- **Font Awesome**: Icons

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📧 Contact Form

The contact form includes:
- Name, email, phone, and message fields
- Service selection dropdown
- Form validation
- Success/error notifications
- Simulated form submission

**Note**: The form currently simulates submission. To make it functional, you'll need to:
1. Set up a backend server
2. Configure email sending (e.g., using Node.js, PHP, or a form service)
3. Update the JavaScript to send data to your server

## 🚀 Deployment

To deploy your website:

1. **GitHub Pages**: Upload to a GitHub repository and enable GitHub Pages
2. **Netlify**: Drag and drop the folder to Netlify
3. **Vercel**: Connect your repository to Vercel
4. **Traditional Hosting**: Upload files to any web hosting service

## 🎯 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Alt text for images
- Proper heading hierarchy
- Fast loading times

## 🔄 Future Enhancements

Consider adding:
- Blog section for photography tips
- Client testimonials
- Pricing packages
- Online booking system
- Image lightbox for portfolio
- Social media integration
- Analytics tracking

## 📞 Support

If you need help customizing the website:
1. Check the HTML comments for guidance
2. Review the CSS variables for easy color changes
3. Test changes in a browser developer console
4. Use browser developer tools to inspect elements

## 🎨 Color Palette

The website uses a carefully selected color palette:

- **Primary Red**: #e63946 (Vibrant red for accents)
- **Dark Red**: #c1121f (Deeper red for gradients)
- **Primary Grey**: #2b2d42 (Medium grey for sections)
- **Dark Grey**: #1a1b26 (Dark background)
- **Light Grey**: #8d99ae (Text and subtle elements)
- **White**: #ffffff (Text and highlights)

This creates a professional, futuristic look that perfectly complements your camera lens logo!

---

**Enjoy your new photography website!** 📸✨ # Reddot-1
