# Anurag Pant - Portfolio Website

A modern, responsive portfolio website showcasing my skills as a Full-Stack Developer.

## 🚀 Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Space-themed design with smooth animations
- **Contact Form** - Integrated with EmailJS for real email functionality
- **SEO Optimized** - Meta tags and structured content
- **Performance Optimized** - Minified CSS/JS for production

## 🛠️ Build System

This project includes a complete build system for production deployment.

### Prerequisites

```bash
npm install
```

### Available Scripts

#### Development
```bash
npm run dev          # Start development server with live reload
```

#### Production Build
```bash
npm run build        # Build optimized production files to dist/
npm run serve        # Serve the production build locally
npm run deploy       # Build and prepare for deployment
```

#### Individual Build Steps
```bash
npm run clean        # Remove dist/ folder
npm run copy         # Copy all files to dist/
npm run minify-css   # Minify CSS files
npm run minify-js    # Minify JavaScript files
npm run optimize-images # Optimize images
```

## 📁 Project Structure

```
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # Source CSS
├── js/
│   └── script.js           # Source JavaScript
├── assets/
│   ├── astro.webp          # Hero image
│   └── favicon.ico         # Website icon
├── dist/                   # Production build (generated)
│   ├── index.html          # Optimized HTML
│   ├── css/
│   │   └── styles.min.css  # Minified CSS
│   ├── js/
│   │   └── script.min.js   # Minified JavaScript
│   └── assets/             # Optimized images
├── package.json            # Build configuration
└── README.md              # This file
```

## 🚀 Deployment

### Option 1: Netlify
1. Run `npm run build`
2. Upload the `dist/` folder to Netlify
3. Your site will be live!

### Option 2: Vercel
1. Run `npm run build`
2. Upload the `dist/` folder to Vercel
3. Automatic deployments on git push

### Option 3: GitHub Pages
1. Run `npm run build`
2. Push the `dist/` folder to a `gh-pages` branch
3. Enable GitHub Pages in repository settings

## 📧 Contact Form Setup

The contact form uses EmailJS for sending emails. To set up:

1. Create an account at [EmailJS.com](https://www.emailjs.com/)
2. Add an email service (Gmail, Outlook, etc.)
3. Create an email template with variables:
   - `{{from_name}}` - Sender's name
   - `{{from_email}}` - Sender's email
   - `{{subject}}` - Email subject
   - `{{message}}` - Email message
4. Update the JavaScript with your credentials:
   - Public Key
   - Service ID
   - Template ID

## 🎨 Customization

### Colors
Update CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #ff6b35;
    --secondary-color: #1a1a2e;
    --accent-color: #16213e;
    /* ... */
}
```

### Content
- Update personal information in `index.html`
- Modify experience, projects, and skills sections
- Replace images in `assets/` folder

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 🤝 Contact

- **Email**: pantanurag1999@gmail.com
- **LinkedIn**: [Anurag Pant](https://linkedin.com/in/anurag-pant-3a0474163)
- **GitHub**: [AnuragPant01](https://github.com/AnuragPant01) 
