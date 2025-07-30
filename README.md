# Asavela Ngqose - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Software Developer.

## 🌟 Features

- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Interactive Typewriter Effect** - Dynamic text animation on the homepage
- **Smooth Scrolling Navigation** - Seamless navigation between sections
- **CV Download** - Direct download functionality for my resume
- **Contact Form** - Integrated contact form using Web3Forms
- **Project Showcase** - Interactive project gallery with hover effects
- **Skills Visualization** - Progress bars showing technical proficiencies

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling with Flexbox and Grid
- **JavaScript** - Interactive functionality and animations
- **Google Fonts** - Poppins font family
- **Boxicons** - Icon library for UI elements
- **Web3Forms** - Contact form handling
- **ScrollReveal** - Scroll animations

## 📁 Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   └── img/                # Image assets
│       ├── perfil.jpg      # Profile image
│       ├── about.jpg       # About section image
│       └── work*.jpg       # Project thumbnails
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for modifications)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AsavelaNgqose/portfolio-website.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd portfolio-website
   ```

3. **Open in your browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server like Live Server in VS Code

### Live Preview

You can also view the live version at: [Your GitHub Pages URL]

## 📱 Sections

### Home
- Interactive typewriter animation
- Social media links (LinkedIn, Behance, GitHub)
- Call-to-action buttons

### About
- Personal introduction and background
- Tabbed content for Education and Experience
- Professional summary

### Skills
- Technical skills with proficiency indicators
- HTML5, Visual Basic, Python, Java

### Projects
- Interactive project gallery
- Hover effects with project descriptions
- Links to live demos and GitHub repositories

### Contact
- Functional contact form
- Direct integration with Web3Forms
- Form validation and success feedback

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy theming:

```css
:root {
  --hue-color: 224;
  --first-color: hsl(var(--hue-color), 89%, 60%);
  --second-color: hsl(var(--hue-color), 56%, 12%);
}
```

### Content Updates
- Update personal information in `index.html`
- Replace project images in `assets/img/`
- Modify project links and descriptions
- Update social media links

### Adding New Projects
1. Add project image to `assets/img/`
2. Create new project item in the work section:
```html
<div class="work__item">
    <a href="your-project-link" target="_blank" class="work__img">
        <img src="assets/img/your-image.jpg" alt="Project Name">
        <div class="work__overlay">
            <div class="work__overlay-content">
                <h3 class="work__overlay-title">Project Name</h3>
                <p class="work__overlay-subtitle">Click to view on GitHub</p>
            </div>
        </div>
    </a>
</div>
```

## 📋 Contact Form Setup

The contact form uses Web3Forms. To set up your own:

1. Visit [Web3Forms](https://web3forms.com/)
2. Get your access key
3. Replace the access key in the HTML:
```html
<input type="hidden" name="access_key" value="your-access-key-here">
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance Features

- Optimized images
- Minified CSS and JavaScript
- Efficient animations
- Mobile-first responsive design
- Fast loading times

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Asavela Ngqose**
- LinkedIn: [Asavela Ngqose](https://www.linkedin.com/in/asavela-ngqose-976a1816a/)
- GitHub: [@AsavelaNgqose](https://github.com/AsavelaNgqose)

## 🙏 Acknowledgments

- [Poppins Font](https://fonts.google.com/specimen/Poppins) by Google Fonts
- [Boxicons](https://boxicons.com/) for the icon library
- [Web3Forms](https://web3forms.com/) for contact form handling
- [ScrollReveal](https://scrollrevealjs.org/) for scroll animations

## 📞 Support

If you have any questions or need support, please feel free to reach out through the contact form on the website or create an issue in this repository.

---

⭐ **Star this repository if you found it helpful!**
