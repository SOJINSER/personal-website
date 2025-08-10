# Personal Website

A modern, responsive personal website built with HTML5, CSS3, and JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## 🚀 Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and smooth transitions
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Seamless navigation between sections
- **Performance Optimized**: Fast loading with optimized CSS and JavaScript

## 📁 File Structure

```
vidhu web/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Download/Clone**: Save all files to your local directory
2. **Open**: Double-click `index.html` or open it in your web browser
3. **Customize**: Edit the content in `index.html` to personalize your website
4. **Deploy**: Upload files to your web hosting service

## 🎨 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Full-Stack Developer & Creative Problem Solver</p>
```

#### About Section
```html
<p>I'm a passionate developer with a love for creating meaningful digital experiences...</p>
```

#### Contact Information
```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Country</span>
```

### Skills & Technologies
Modify the skills section to match your expertise:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

### Projects
Update the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### Social Links
Update your social media links:

```html
<div class="social-links">
    <a href="your-github" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

## 🎯 Color Scheme

The website uses a modern color palette:

- **Primary**: `#667eea` (Blue)
- **Secondary**: `#764ba2` (Purple)
- **Accent**: `#ffd89b` (Gold)
- **Text**: `#2d3748` (Dark Gray)
- **Background**: `#f7fafc` (Light Gray)

To change colors, edit the CSS variables in `styles.css`.

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Advanced Customization

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add JavaScript functionality in `script.js` if needed

### Modifying Animations
Edit the CSS transitions and JavaScript animation functions:

```css
/* In styles.css */
.fade-in {
    opacity: 0;
    transform: translateY(30px);
    transition: all 0.6s ease;
}
```

### Custom Fonts
Replace the Google Fonts link in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Then update the font-family in `styles.css`:

```css
body {
    font-family: 'YourFont', sans-serif;
}
```

## 🚀 Deployment

### GitHub Pages
1. Create a new repository
2. Upload your website files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your website folder to Netlify
2. Your site will be live instantly
3. Customize the domain if needed

### Traditional Hosting
1. Upload files via FTP/SFTP
2. Ensure `index.html` is in the root directory
3. Test all functionality

## 📊 Performance Tips

- **Optimize Images**: Use WebP format and compress images
- **Minify CSS/JS**: Use tools like UglifyJS and CSSNano
- **Enable Gzip**: Compress files on your server
- **Use CDN**: Font Awesome and Google Fonts are already CDN-hosted

## 🐛 Troubleshooting

### Common Issues

**Navigation not working**: Check if `script.js` is properly linked
**Styles not loading**: Verify `styles.css` path is correct
**Mobile menu not working**: Ensure JavaScript is enabled
**Form not submitting**: Check browser console for errors

### Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve this template.

## 📞 Support

If you need help customizing your website:
1. Check this README first
2. Review the code comments
3. Search for similar issues online
4. Create a detailed issue description

---

**Happy Coding! 🎉**

Your personal website is now ready to showcase your skills and projects to the world!
