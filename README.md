# Jotiba Jadhav - Data Analytics Professional Portfolio

A modern, responsive portfolio website built with HTML, CSS, JavaScript, and Bootstrap to showcase data analytics expertise, projects, and professional experience.

## 🌟 Features

- **Responsive Design**: Fully responsive and works seamlessly on all devices
- **Modern UI**: Clean, professional design with smooth animations
- **Sections Included**:
  - Hero/Home Section with social links
  - About Me with statistics
  - Skills with progress bars
  - Professional Experience with timeline
  - Featured Projects with categorized cards
  - Certifications & Education
  - Contact Information

- **Interactive Elements**:
  - Smooth scrolling navigation
  - Active navigation highlighting
  - Scroll progress indicator
  - Hover animations and transitions
  - Fade-in animations on scroll
  - Mobile-responsive hamburger menu

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 How to Use

1. **Open in Browser**: Simply open `index.html` in your web browser
   - Double-click the `index.html` file, or
   - Right-click and select "Open with" your preferred browser

2. **Local Server (Recommended)**:
   - Using Python: `python -m http.server 8000` then navigate to `http://localhost:8000`
   - Using Node.js: Install `http-server` globally with `npm install -g http-server`, then run `http-server`
   - Using VS Code: Install "Live Server" extension and click "Go Live"

3. **Deploy Online**:
   - GitHub Pages: Push to a GitHub repository and enable Pages in settings
   - Netlify: Drag and drop the folder or connect your Git repository
   - Vercel: Connect your Git repository

## 🎨 Customization Guide

### Update Personal Information
Edit the following in `index.html`:
- Name and titles in the hero section
- Contact information (phone, email, location)
- Social media links (LinkedIn, GitHub)
- All resume content

### Modify Colors
Edit color variables in `styles.css`:
```css
:root {
    --primary-color: #0d6efd;
    --secondary-color: #6c757d;
    --success-color: #198754;
    --danger-color: #dc3545;
    --dark-color: #212529;
    --light-color: #f8f9fa;
    --gradient: linear-gradient(135deg, #0d6efd 0%, #0dcaf0 100%);
}
```

### Change Font
Modify the font-family in `styles.css`:
```css
body {
    font-family: 'Your Font Name', sans-serif;
}
```

### Add Profile Picture
Replace the `.animated-box` div with an image tag in the hero section:
```html
<img src="your-image.jpg" alt="Profile" class="profile-image" style="width: 100%; border-radius: 20px;">
```

### Add More Projects
Copy a project card in the projects section and update:
```html
<div class="col-md-6 col-lg-4 mb-4">
    <div class="project-card">
        <div class="project-header bg-primary">
            <i class="fas fa-icon"></i>
        </div>
        <div class="project-body">
            <h5>Project Name</h5>
            <p class="text-muted small">Category - Date</p>
            <p>Project description</p>
            <div class="project-tags">
                <span class="badge bg-info">Tag1</span>
                <span class="badge bg-info">Tag2</span>
            </div>
        </div>
    </div>
</div>
```

## 🔧 Browser Compatibility

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- Desktop: 1024px and above
- Tablet: 768px to 1023px
- Mobile: Below 768px

## 🎯 Performance Features

- Optimized CSS with efficient selectors
- Smooth animations without excessive resource usage
- Bootstrap CDN for lightweight framework
- Font Awesome icons from CDN
- Minimal JavaScript for better performance

## 📚 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Grid, Flexbox, Animations, Gradients
- **JavaScript (ES6)**: DOM manipulation, Intersection Observer
- **Bootstrap 5**: Responsive grid system and components
- **Font Awesome 6**: Icon library

## 🔗 External Resources

- Bootstrap: https://getbootstrap.com/
- Font Awesome: https://fontawesome.com/
- Google Fonts: https://fonts.google.com/

## 📝 Notes

- All links are functional and point to actual profiles/emails
- The portfolio is fully self-contained (no external dependencies except CDNs)
- All animations are GPU-optimized for smooth performance
- Mobile menu auto-closes when navigating to sections

## 🤝 Support

For customizations or questions, feel free to reach out:
- Email: jadhavjotiba373@gmail.com
- LinkedIn: linkedin.com/in/jotiba-jadhav-3406871b5
- GitHub: github.com/jjadhav373

## 📄 License

This portfolio is free to use and modify for personal use.

---

**Happy showcasing your portfolio! 🚀**
