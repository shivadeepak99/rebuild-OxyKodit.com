# OxyKodit.com - Modern Rebuild

A modern, responsive rebuild of the OxyKodit website using TailwindCSS, preserving the original design and content while implementing modern web standards and best practices.

## 🎯 Project Overview

This project is a faithful recreation of [OxyKodit.com](https://oxykodit.com), the professional website of Sofie Van Landeghem (svlandeg), a Data Scientist and Machine Learning Engineer specializing in Natural Language Processing (NLP) solutions. The original site was built with WordPress and Bootstrap but needed modernization for better performance, accessibility, and maintainability.

## 🚀 Features

- **Modern Stack**: Built with HTML5, TailwindCSS, and Vanilla JavaScript
- **Responsive Design**: Fully responsive across all device sizes
- **Accessibility**: WCAG compliant with proper semantic markup
- **Performance**: Optimized for fast loading and smooth animations
- **SEO Friendly**: Proper meta tags and structured markup
- **Cross-browser**: Compatible with all modern browsers

## 🏗️ Architecture

### Original Structure Recreated:
- **Header**: Parallax mountain landscape with hero text
- **Introduction**: Personal bio and expertise overview
- **Projects**: Three main service offerings with detailed breakdowns
- **Blog**: Featured blog posts with responsive card layout
- **Contact**: Social media links and contact information
- **Navigation**: Smooth scrolling navigation with scroll behavior

### Key Sections:
1. **AI Proof-of-Concept** - Custom AI solution development
2. **Production-Grade Code** - Code optimization and testing
3. **Open-Source Maintenance** - Community-driven development

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with accessibility features
- **TailwindCSS**: Utility-first CSS framework
- **Vanilla JavaScript**: Smooth scrolling and navigation behavior
- **Font Awesome**: Social media and UI icons
- **Google Fonts**: Inter (body) and Cardo (headings)

## 📁 Project Structure

```
rebuild-OxyKodit.com/
├── index.html              # Main HTML file
├── styles.css              # Additional custom CSS
├── images/                 # Image assets directory
│   ├── OxyKodit_Logo_empty.png
│   ├── services-icon-png-2302.png
│   ├── Blog.jpg
│   ├── inside_the_black_box.png
│   ├── keynote_pyconitalia.jpg
│   └── 2024_01_23_az.png
├── README.md               # This file
└── .gitignore              # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A local web server (optional, but recommended)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shivadeepak99/rebuild-OxyKodit.com.git
   cd rebuild-OxyKodit.com
   ```

2. **Add the required images:**
   - Download the original images from the live site or create placeholders
   - Place them in the `images/` directory
   - Ensure proper naming as referenced in `index.html`

3. **Serve the website:**
   
   **Option A: Using Python (if installed):**
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

   **Option B: Using Node.js (if installed):**
   ```bash
   npx serve .
   ```

   **Option C: Using VS Code Live Server:**
   - Install the "Live Server" extension
   - Right-click on `index.html` and select "Open with Live Server"

   **Option D: Direct file access:**
   - Simply open `index.html` in your browser (some features may not work due to CORS)

## 🌐 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

### Netlify
1. Drag and drop the project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository for automatic deployments

## �� Customization

### Colors
The site uses a custom color palette defined in the Tailwind config:
- `oxy-primary`: #669990 (teal green)
- `oxy-dark`: #324a51 (dark blue-gray)
- `oxy-light`: #6f8085 (light blue-gray)
- `oxy-bg`: #f9f9f9 (light background)

### Fonts
- **Headings**: Cardo (serif)
- **Body**: Inter (sans-serif)

### Responsive Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 Development

### Adding New Sections
1. Add the HTML structure following the existing pattern
2. Use Tailwind utility classes for styling
3. Update navigation links if needed
4. Test responsiveness across devices

### Modifying Styles
- Primary styling uses Tailwind utilities
- Custom CSS goes in `styles.css`
- Follow the existing naming conventions

### JavaScript Enhancements
Current JavaScript handles:
- Smooth scrolling navigation
- Scroll-based navigation visibility
- Header text fade effect
- Current year auto-update

## 🧪 Testing

### Browser Testing
Test in the following browsers:
- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Responsive Testing
- Mobile devices (320px - 768px)
- Tablets (768px - 1024px)
- Desktop (1024px+)

### Accessibility Testing
- Screen reader compatibility
- Keyboard navigation  
- Color contrast ratios
- Focus indicators

## 🤝 Contributing

This project is a tribute to the original OxyKodit website. If you would like to contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 🙏 Acknowledgments

- **Original Creator**: [Sofie Van Landeghem (svlandeg)](https://github.com/svlandeg) - The original OxyKodit website and content
- **Design Inspiration**: The original OxyWeb repository and live OxyKodit.com site
- **Tools Used**: TailwindCSS, Font Awesome, Google Fonts

## 📄 License

This project is created as a tribute to preserve the digital footprint of the original OxyKodit website. All content belongs to the original creator, Sofie Van Landeghem.

## 📞 Contact

**Rebuilt by**: [shivadeepak99](https://github.com/shivadeepak99)  
**Original**: [sofie@oxykodit.com](mailto:sofie@oxykodit.com)

---

> "Site lovingly rebuilt by shivadeepak99 — tribute to svlandeg's original OxyWeb (2017)."
