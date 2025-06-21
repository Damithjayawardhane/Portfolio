# Chathura Jayawardhane - Software Engineer Portfolio

A modern, responsive, and interactive portfolio website showcasing the professional experience, skills, and projects of Chathura Jayawardhane, a Software Engineer with over 5 years of experience in web and mobile development.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🌟 Live Demo

**Visit the portfolio:** [Chathura Jayawardhane - Software Engineer](https://your-portfolio-url.com)

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Sections Overview](#sections-overview)
- [Installation & Setup](#installation--setup)
- [Customization Guide](#customization-guide)
- [Performance & Optimization](#performance--optimization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## 👨‍💻 About

This portfolio represents the professional journey of **Chathura Jayawardhane**, a passionate Software Engineer with expertise in:

- **Full-Stack Development**: Angular, React, .NET Core, Java
- **Mobile Development**: React Native
- **Database Management**: MySQL, Oracle, SQL Server, PostgreSQL
- **DevOps & Tools**: Git, JIRA, Visual Studio, VS Code

The portfolio showcases a comprehensive collection of professional projects, technical skills, and career achievements in an elegant, modern interface.

## ✨ Features

### 🎨 Design & User Experience
- **Modern Glass Morphism**: Elegant transparent navigation with backdrop blur effects
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: CSS animations and JavaScript interactions for enhanced UX
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic navigation
- **Professional Color Scheme**: Blue gradient theme with excellent contrast ratios
- **Typography**: Clean, readable Inter font family throughout

### 🚀 Technical Features
- **Mobile-First Approach**: Responsive navigation with hamburger menu
- **Form Validation**: Client-side email validation with user feedback
- **Smooth Scrolling**: Anchor link navigation with smooth scrolling behavior
- **Intersection Observer**: Scroll-triggered animations for better performance
- **Notification System**: Success/error notifications for form submissions
- **Active Navigation**: Dynamic highlighting of current section
- **Loading Animations**: Page load animations and typing effects

### 📱 Responsive Features
- **Adaptive Layout**: Grid and flexbox layouts that adapt to screen size
- **Touch-Friendly**: Optimized touch targets for mobile devices
- **Mobile Navigation**: Collapsible hamburger menu for mobile
- **Image Optimization**: Responsive images with proper aspect ratios

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: Advanced styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)**: Modern JavaScript with async/await and DOM manipulation
- **Font Awesome**: Professional icons for skills and social links
- **Google Fonts**: Inter font family for clean typography

### Development Tools
- **Visual Studio Code**: Primary development environment
- **Git**: Version control and collaboration
- **Chrome DevTools**: Debugging and performance optimization

## 📄 Sections Overview

### 1. **Hero Section**
- Professional introduction with animated profile image
- Call-to-action buttons (View My Work, Get In Touch)
- Social media links (GitHub, LinkedIn)
- Animated background with floating elements

### 2. **About Section**
- Professional summary and background
- Personal motto and career philosophy
- Professional image with hover effects
- Key statistics and achievements

### 3. **Experience Timeline**
- Chronological work experience
- Company names and positions
- Duration and responsibilities
- Visual timeline with connecting elements

### 4. **Skills & Technologies**
- **Web Technologies**: HTML, CSS, Angular, React, Bootstrap
- **Programming Languages**: Java, C#, JavaScript, TypeScript
- **Frameworks & Libraries**: .NET Core, React Native, PrimeNG
- **Databases**: MySQL, Oracle, SQL Server, PostgreSQL
- **Development Tools**: Visual Studio, VS Code, IntelliJ IDEA
- **Version Control**: Git, GitBucket
- **Project Management**: JIRA
- **Testing**: Jasmine Framework

### 5. **Projects Portfolio**
- **Professional Projects**: Insurance systems, tender websites, course management
- **Personal Projects**: Overtime calculator, mobile applications
- **Academic Projects**: Research projects, university assignments
- Each project includes:
  - Project image and description
  - Technology stack used
  - Live demo links (where available)
  - Detailed responsibilities and contributions

### 6. **Education & Qualifications**
- **Academic Background**: BSc (Hons) in Information Technology from SLIIT
- **Professional Certifications**: Multiple certificates in various technologies
- **Timeline Layout**: Clean chronological presentation

### 7. **Contact Section**
- Contact form with validation
- Personal contact information
- Social media links
- Professional call-to-action

## 🚀 Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your web browser
   # Or use a local server for development
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Customize content**
   - Update personal information in `index.html`
   - Modify styles in `styles.css`
   - Adjust functionality in `script.js`

### File Structure
```
Portfolio/
├── index.html              # Main HTML structure
├── styles.css              # CSS styles and animations
├── script.js               # JavaScript functionality
├── Chathura-img.png        # Profile image
├── Chathura-middle.jpg     # About section image
└── README.md               # Project documentation
```

## 🎨 Customization Guide

### Personal Information
Update the following in `index.html`:

```html
<!-- Hero Section -->
<h1 class="hero-title">Your Name</h1>
<h2 class="hero-subtitle">Your Title</h2>
<p class="hero-description">Your professional description</p>

<!-- Contact Information -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
```

### Images
- **Profile Image**: Replace `Chathura-img.png` with your photo
- **About Image**: Replace `Chathura-middle.jpg` with your about section image
- **Project Images**: Update project images with actual screenshots

### Skills & Technologies
Modify the skills section to match your expertise:

```html
<div class="skill-card">
    <h3>Your Skill Category</h3>
    <div class="skill-tags">
        <span><i class="fab fa-your-icon"></i> Technology Name</span>
    </div>
</div>
```

### Projects
Update projects with your actual work:

```html
<div class="project-card-redesigned">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <h4>Company/Organization</h4>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
    </div>
</div>
```

### Color Scheme
Customize colors in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue */
    --secondary-color: #1e40af;    /* Darker blue */
    --accent-color: #fbbf24;       /* Accent color */
    --text-primary: #0f172a;       /* Primary text */
    --text-secondary: #334155;     /* Secondary text */
    --background-light: #f8fafc;   /* Light background */
}
```

## ⚡ Performance & Optimization

### Current Optimizations
- **CSS Animations**: Hardware-accelerated transforms
- **Lazy Loading**: Images load as needed
- **Minified Assets**: Optimized file sizes
- **Efficient Selectors**: Fast CSS selectors

### Recommended Improvements
- **Image Compression**: Compress images for faster loading
- **CDN Integration**: Use CDN for external resources
- **Service Worker**: Add offline functionality
- **Analytics**: Implement user behavior tracking

## 🌐 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 60+ | ✅ Full Support |
| Firefox | 55+ | ✅ Full Support |
| Safari | 12+ | ✅ Full Support |
| Edge | 79+ | ✅ Full Support |
| IE | 11 | ⚠️ Limited Support |

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style and formatting
- Test on multiple browsers and devices
- Ensure responsive design works correctly
- Update documentation for any new features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact & Support

- **Portfolio**: [Live Website](https://your-portfolio-url.com)
- **Email**: damithjayawardhane@gmail.com
- **LinkedIn**: [Chathura Jayawardhane](https://www.linkedin.com/in/damithjayawardhane/)
- **GitHub**: [Damithjayawardhane](https://github.com/Damithjayawardhane)

## 🙏 Acknowledgments

- **Font Awesome** for the beautiful icons
- **Google Fonts** for the Inter font family
- **Unsplash** for placeholder images
- **CSS Grid & Flexbox** for modern layouts
- **Intersection Observer API** for scroll animations

---

**Built with ❤️ and lots of ☕ by Chathura Jayawardhane**

*This portfolio showcases the journey of a passionate Software Engineer dedicated to creating exceptional digital experiences.*
