# Damien Tsarantos Portfolio

A modern, interactive portfolio website showcasing the work of Damien Tsarantos, a Creative Director specializing in web design and front-end development.

## 🎯 Overview

This is a professional portfolio website built with vanilla HTML, CSS, and JavaScript. It features smooth animations, interactive elements, and a sophisticated design that showcases creative work in an engaging way.

## ✨ Features

### Core Features
- **Multi-page Portfolio**: Home, About, Projects, Awards, and Contact pages
- **Interactive Animations**: Smooth scroll effects, magnetic hover interactions, and text animations
- **Responsive Design**: Modern, minimalist aesthetic with large typography
- **Project Showcase**: Grid-based layout displaying 9 featured projects
- **Professional Presentation**: Dark theme with sophisticated visual hierarchy

### Technical Features
- **Smooth Scrolling**: Enhanced scrolling experience with Lenis library
- **GSAP Animations**: Advanced animations using GreenSock Animation Platform
- **Custom Typography**: PP Neue Montreal font family
- **Modular CSS**: Organized stylesheets for maintainability
- **Performance Optimized**: Efficient animations and smooth interactions

## 🛠️ Technology Stack

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: No framework dependencies

### Libraries & Dependencies
- **GSAP (GreenSock)**: Animation library for smooth effects
  - Version: 3.12.5
  - Includes ScrollTrigger plugin (3.11.0)
- **Lenis**: Smooth scrolling library
  - Version: 1.1.5
- **Ionicons**: Icon library
  - Version: 7.1.0
- **TweenMax**: Animation library (legacy GSAP)
  - Used for magnetic hover effects

### Typography
- **PP Neue Montreal**: Custom font family with multiple weights
  - Includes: Thin, Light, Regular, Medium, Book, Bold variants
  - Both TTF and OTF formats available

## 📁 Project Structure

```
damien-tsarantos/
├── index.html                 # Main homepage
├── css/                       # Stylesheets
│   ├── global.css            # Global styles and variables
│   ├── nav.css               # Navigation styles
│   ├── home.css              # Homepage specific styles
│   ├── about.css             # About page styles
│   ├── work.css              # Work/Projects page styles
│   ├── project.css           # Individual project page styles
│   ├── awards.css            # Awards page styles
│   └── contact.css           # Contact page styles
├── js/
│   └── script.js             # Main JavaScript functionality
├── pages/                    # Additional pages
│   ├── about.html            # About page
│   ├── work.html             # Projects showcase
│   ├── project.html          # Individual project details
│   ├── awards.html           # Awards and recognition
│   └── contact.html          # Contact information
├── assets/                   # Media assets
│   ├── work/                 # Project images
│   │   ├── img1.jpg - img9.jpg
│   │   └── project-*.png     # Additional project assets
│   ├── contact-dark.png      # Contact page graphics
│   └── contact-light.png     # Contact page graphics
└── Fonts/                    # Typography
    └── PP Neue Montreal/     # Custom font files
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (for development)

### Local Development Setup

1. **Clone or Download the Project**
   ```bash
   # If using git
   git clone [repository-url]
   cd damien-tsarantos
   
   # Or simply download and extract the files
   ```

2. **Set Up a Local Server**
   
   **Option 1: Using Python (Recommended)**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

   **Option 2: Using Node.js**
   ```bash
   # Install a simple HTTP server globally
   npm install -g http-server
   
   # Run the server
   http-server -p 8000
   ```

   **Option 3: Using PHP**
   ```bash
   php -S localhost:8000
   ```

   **Option 4: Using Live Server (VS Code Extension)**
   - Install the "Live Server" extension in VS Code
   - Right-click on `index.html` and select "Open with Live Server"

3. **Access the Website**
   - Open your browser and navigate to `http://localhost:8000`
   - The portfolio should load with all animations and interactions working

### Important Notes
- **Local Server Required**: Due to CORS policies and external dependencies, the website must be served from a web server (not opened directly as a file)
- **Internet Connection**: The website loads external libraries (GSAP, Lenis, Ionicons) from CDNs, so an internet connection is required

## 🌐 Deployment

### Static Hosting (Recommended)

This is a static website that can be deployed to any static hosting service:

#### 1. **Netlify**
```bash
# Drag and drop the entire project folder to Netlify
# Or connect your Git repository
```

#### 2. **Vercel**
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

#### 3. **GitHub Pages**
```bash
# Push to GitHub repository
# Enable GitHub Pages in repository settings
# Set source to main branch
```

#### 4. **Firebase Hosting**
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Initialize and deploy
firebase init hosting
firebase deploy
```

#### 5. **Traditional Web Hosting**
- Upload all files to your web hosting provider
- Ensure the file structure is maintained
- Set `index.html` as the default document

### Server Requirements
- **Web Server**: Apache, Nginx, or any static file server
- **HTTPS**: Recommended for production (most hosting providers include this)
- **File Permissions**: Ensure all files are readable by the web server

## 📱 Browser Compatibility

### Supported Browsers
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Features by Browser
- **Modern Browsers**: Full functionality with all animations
- **Older Browsers**: Basic functionality, animations may be limited
- **Mobile Browsers**: Responsive design with touch-friendly interactions

## 🎨 Customization

### Content Updates
1. **Project Information**: Edit project details in HTML files
2. **Images**: Replace images in `assets/work/` directory
3. **Text Content**: Update text content in respective HTML files
4. **Contact Information**: Modify contact details in `contact.html`

### Styling Changes
1. **Colors**: Update CSS variables in `css/global.css`
2. **Typography**: Replace font files in `Fonts/` directory
3. **Layout**: Modify CSS files for layout changes
4. **Animations**: Adjust animation parameters in `js/script.js`

### Adding New Projects
1. Add project images to `assets/work/`
2. Update project grid in `index.html` and `work.html`
3. Create individual project pages if needed
4. Update navigation and links accordingly

## 🔧 Troubleshooting

### Common Issues

1. **Animations Not Working**
   - Ensure internet connection for CDN libraries
   - Check browser console for JavaScript errors
   - Verify GSAP and Lenis are loading correctly

2. **Fonts Not Loading**
   - Check font file paths in CSS
   - Ensure font files are in the correct directory
   - Verify font-face declarations in CSS

3. **Images Not Displaying**
   - Check image file paths
   - Ensure images are in the correct directory
   - Verify file permissions

4. **Smooth Scrolling Issues**
   - Ensure Lenis library is loading
   - Check for JavaScript errors in console
   - Verify browser compatibility

### Performance Optimization
- **Image Optimization**: Compress images for faster loading
- **Font Loading**: Consider using font-display: swap for better performance
- **Animation Performance**: Monitor frame rates on mobile devices

## 📄 License

This project is a portfolio template. Please ensure you have the right to use any included assets, fonts, or content for your own projects.

## 🤝 Support

For technical support or questions about this portfolio template:
- Check the browser console for error messages
- Verify all dependencies are loading correctly
- Ensure you're running the site from a web server, not as a local file

## 📞 Contact

For questions about the original design or implementation:
- **Design**: @Codegrid
- **Portfolio Subject**: Damien Tsarantos

---

**Note**: This is a static website that showcases creative work with modern web technologies. All animations and interactions are client-side and require no backend services.
